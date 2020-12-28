# Speech Denoising using 2D CNN

### Data overview
- The data consists of two male speech signals. One of them is noisy and other is clean
- For testing purposes, I am using two test noisy signals

### Modelling
- The signals are loaded using librosa and then short time fourier transform is done to convert signals into magnitude spectograms
- Image of 20 X 513 is extracted out of entire spectograms. Using this 2D CNN estimates cleaned-up spectograms that corresponds to the last 20th input frame. 
- The next image will be shifted by one frame and the model will predict the clean spectrum of the current frame
- Padding is done to ensure consistency in spectograms 

## Signal to Noise Ratio
- SNR is used for validating the model performance. The SNR value for training signal is around 17
