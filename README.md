# Emotive   
### Emotion Recognition in Speech   
#### Bach Le, Kien Tran, Suaryanshu Khanal and Sike Ogieva

The aim of this project was to build and train neural networks to recognise the emotion in human speech. 

We began by looking at previous literature to guide the building of our model. Then we analyze the RAVDESS for quality (both by ensuring that feature distribution is even, and that there are considerable audio-qualitative differences between files of different emotions). Then we augment our training files to increase them from 1_400 to 12_000 by adding noise, stretching, shifting and changing pitch. We selected the Mel Frequency Cepstral Coefficients as our features and extracted 40 of them per audio file. 

The models we built were k-Nearest Neighbors, Multilayer Perceptron,  Convolutional Neural Network, Long Short Term Memory Neural Network, Combined (CNN + LSTM)  Neural Network, and a Bidirectional LSTM Neural Network. Their performance was as follows.  

![speech-recognition-model-performance](https://github.com/sike25/emotive/assets/97693483/82439903-fb65-45be-a72f-817373dd9d40)

### Note
Each milestone's directory contains detailed pdf reports and references on our work at that stage. The final presentation (uploaded) should also serve as a useful guide.
