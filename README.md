This project was developed as a final project for the Neural Networks and Deep Learning course at the University of Padova for the Information and Communication Technologies (ICT) master's degree program. In this project, we attempt to solve the music genre classification problem using the Free Music Archive dataset and 3 different convolutional neural network (CNN) architectures. The entire report with details can be found [here](NNDL_Final_Project_Nico_Ortiz_de_Zarate.pdf).

## Data
We use the Free Music Archive (FMA) dataset, specifically the small version containing 8,000 tracks of 30 seconds and 8 balanced genres. The GitHub repo containing all versions of the data as well as their detailed descriptions can be found [here](https://github.com/mdeff/fma).


## Task 
We attempt to build and train several different CNN models to classify audio tracks into one of 8 different genres:  Hip-Hop, Rock, Pop, Folk, Experimental, International, Electronic, and Instrumental. The three different architectures are as follows:

1. 1-Dimensional CNN using raw audio signals as input
![1-Dimensional model architecture](https://github.com/nortizde/Music-Genre-Classification/blob/main/figures/oneDModel.drawio.pdf)
3. 2-Dimensional CNN using Mel spectrogram representation of audio as input
![2-Dimensional model architecture](https://github.com/nortizde/Music-Genre-Classification/blob/main/figures/twoDmodel.png)
5. Combined CNN model that uses both 1-D audio and 2-D Mel spectrogram as input
![Combined model architecture](https://github.com/nortizde/Music-Genre-Classification/blob/main/figures/combined_model.drawio.pdf)

## Results
All three models achieved accuracies over 80% on their respective test sets, as well as precision, recall, and F1 scores in the high 60's. 
