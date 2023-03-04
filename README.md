# Music-Genre-Classification
>Music Classification is task which can be effectively evaluated using the concepts of Deep Learning and Good preprocessing.

>In this project I have created a Convolutional Neural Network to Classify music genres ['reggae', 'jazz', 'country', 'hiphop', 'rock', 'metal', 'classical', 'disco', 'blues', 'pop']. 
>I have Used Librosa to get the sampling rate(sr) and display the mfcc.

>The MFCC feature extraction technique basically includes windowing the signal, applying the DFT, taking the log of the magnitude, and then warping the frequencies on a Mel scale, followed by applying the inverse DCT.In the Notebook Librosa does all of that with a single command.

>This projects uses mfcc of a 30 sec wav file, loads the data in a JSON file, you can see all the preprocessing in the provided notebook.

>The [GTZAN Dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification) was used for Music Genre Classification. 
