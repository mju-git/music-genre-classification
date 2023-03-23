
# Music Genre Classification

Classifying audio files in genres they belong to based on extracted audio data. 

The automation of this process is important because the manual approcah takes extensive time and effort.

The music genre classification can be done using different approaches and the top 4 approaches that are mostly used are: 
- Multiclass support vector machine
- K-Nearest Neighbours
- K-means clustering algorithm
- Convolutional neural network

The dataset used in this project is GTZAN genre collection dataset which consists of 1000 files that belong to 10 different classes. Each of the classes has 100 audio files in waveform audio file format (.wav). The classes are:
- blues 
- hip-hop
- rock
- classical
- disco
- pop
- country
- metal
- jazz
- reggae

The dataset can be found on Kaggle and downloaded [here](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification).

Sound waves are digitized by sampling them at discrete intervals known as the sampling rate (typically 44.1kHz for CD-quality audio meaning samples are taken 44,100 times per second). The more sound data (samples) gathered per period of time, the closer to the original analog sound the captured data becomes.

When a signal is sampled, it needs to store the sampled audio information in bits. This is where the bit depth comes into place. Each sample is the amplitude of the wave at a particular time interval, where the bit depth determines how detailed the sample will be. The higher the number of bits indicates more space for information storage. A sampling with 24-bit depth can store more nuances and hence, more precise than a sampling with 16-bit depth (65536 levels of information).

Another important factor that bit depth affects is the dynamic range of a signal. A 16-bit digital audio has a maximum dynamic range of 96dB.



