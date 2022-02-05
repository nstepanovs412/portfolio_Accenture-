# Portfolio Accenture
Files listed above are the projects I have created myself or participated in. 

Tasks in Computer vision folder 1 - 3 are admission tasks to Charite BIH lab. 
Charite ECG_32 is a project I worked at Charite BIH 




## ECG Charite

There is a dataset of 20K 12 leads ECGS PTBXL https://physionet.org/content/ptb-xl/1.0.0/

The PTB-XL ECG dataset is a large dataset of 21837 clinical 12-lead ECGs from 18885 patients of 10 second length. The raw waveform data was annotated by up to two cardiologists, who assigned potentially multiple ECG statements to each record. 

I ofered instead of using Fourier transformation to apply scalogram conversion as a means of dimensionality reduction.
Fourier transormation preserves either frequency or time domain, but we need both components so scalogram transform was chosen. 

I converted all images into scalograms and fed into a simple network. 

later in BIH I continued to work with this approach but with a different dataset I cannot disclose.
