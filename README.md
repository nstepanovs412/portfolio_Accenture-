# Portfolio Accenture
Files listed above are the projects I have created myself or participated in. 

Task 1 - 3 are admission tasks to Charite BIH lab. 
Charite ECG_32 is a project I worked at Charite BIH 


## **Task 1**

  • Use MNIST dataset to build LeNet model

  • Add dropout 
  
  • Draw graphs for model accuracy and model loss 
  
  • Show how to reshape the dataset and one hot encode it

## **Task 2**

•Import CIFAR-10

•Standartise CIFAR-10

•Build CNN with 1 convolution

•Save network as json

•Draw metrics

Once the above tasks are done improve network

•Add more convolutions

Once the above tasks are done improve dataset

•Generate additional images

•Use augmentation methods


## **Task 3**

There is a dataset of 20K 12 leads ECGS PTBXL https://physionet.org/content/ptb-xl/1.0.0/

The PTB-XL ECG dataset is a large dataset of 21837 clinical 12-lead ECGs from 18885 patients of 10 second length. The raw waveform data was annotated by up to two cardiologists, who assigned potentially multiple ECG statements to each record. 

I ofered instead of using Fourier transformation to apply scalogram conversion as a means of dimensionality reduction.
Fourier transormation preserves either frequency or time domain, but we need both components so scalogram transform was chosen. 

I converted all images into scalograms and fed into a simple network. 

later in BIH I continued to work with this approach but with a different dataset I cannot disclose.
