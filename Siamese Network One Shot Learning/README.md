## Experimentation on Outlier Detection and Zero Shot Learning using Siamese and C2C-Siamese Network

The source code consists of two parts :

### Siamese Network 
- Attached are two files Siamese_network_train.ipynb and Siamese_network_results.ipynb
- Dataset used is Keras MNIST 
- Model training is done on Siamese_network_train.ipynb (you don't need to run this notebook, however you can if you wish to)
- Siamese network model is saved in model-siamese.h5 and anomaly matrix which is used for outlier detection and zero shot learning is saved in anomaly_matrix.npy
- Model and numpy array is loaded on Siamese_network_results.ipynb which produce resultant plots
- .html file is also attached for your reference 

### C2C-Siamese Network
- Attached is one ipynb file named C2C-Siamese_ZSL.ipynb
- Outlier Detection and ZSL through C2C-SN are conducted in the above file
- 36 C2C-SN models for digits from 0-5 are saved in the models folder and so sre the resultant vectors resultPredseen.npy and resultPredunseen.npy for seen and unseen cases respectively.
- There isn't a need to run the whole code. You can directly load the results and run the code after you encounter the markdown describing where to run the code from. However do run the first block of code to import the necessary packages 
