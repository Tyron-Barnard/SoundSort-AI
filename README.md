
# KNN and ANN Classifier for Training Data
-------------------------------------------
The K-Nearest Neighbour (KNN) algorithm assumes that similar items and things that exists in close distances or proximity. In music genre classification, K-Nearest Neighbour (KNN) algorithms help to find out the similar genre of music near to each other and can be beneficial for recommending alike music to listeners. The KNN algorithm will select the right K(n) that is used for labelling the prediction of an actual data. The implementation of KNN is versatile and high accuracy with quick computing calculation time. But, the accuracy of output is totally depending on the properties of data

Artificial neural network (ANN) is simply known as neural network where a system is designed after human brain that also respond and mimic human brain for making decision. The networks of ANN consist of three layers called input layers, output layers and hidden layers. The composition of layers is very similar to the building of neural networks in human brain.  The use of ANN algorithm has been seen in every field like recognizing face when unlocking your phone, classifying images for security and giving command in forms of voice. The implementation of ANN algorithm can handle huge amounts of available data and has higher performing rate. It also solves such problems that human may not be able to figure out. But using ANN, it takes quite longer time for training the model.

==


# Accuracy
--------
** Training (at Epoch 200):
    
    * Training loss:    0.4505
    
    * Training accuracy:    0.7100

 ** Testing:
    
    * Test loss:    3.3788
    
    * Test accuracy:    0.6399

# Dataset Source or Link
----------------------
The dataset is in format of audio i.e wav format consisting of 1000 audio tracks of each ten genres (blues, classical, country, disco, hiphop, jazz, metal, pop, reggae and rock) with lenth of 30 seconds long audio tracks. 
		 

		 


# Overall System Architecture
-----------------------------

![Architecture of Music Genre Classification](https://user-images.githubusercontent.com/59358909/85203957-d9142680-b330-11ea-8feb-091d52a340e5.png)



# Overview & Background
----------------------
Music genres is the taste, style and relax giving flow of a music. The genre of music refers to multiple types and categorization of music. The different types of famous music genre that we widely known are rock, jazz, reggae, classical, folk, blues, R & B, metal, dubstep, techno, country music, electro and pop. The key success of music in music industry is the genres of classified music that becomes a significant part of communicating music that provides bonding with relatively to human and masses of people. In contrast, the genre that falls under top-level style of rock are punk, indie, shoegaze, AOR and metal. They are basically subgenre of a music classification and it is important describing music to other people. In practical life, music is often used for multiple purposes due to physiological and social effects.  

Companies like Spotify, Soundcloud, Apple Music, Wynk & products like Shazam use music classification to provide their customers different flavour of music by recommending music they prefer to listen. we use python libraries such as Librosa and PyAudio library for audio processing in Python. We apply and use GTZAN dataset that is composed of 1000 audio tracks each 30-second-long representing 10 genres with 22050Hz mono audio file of 16bit in .au format for dataset. The functionality and working of music genre classification determine the help of Machine Learning algorithms. The algorithm such as KNN and artificial neural network (ANN) analyses and find out the similar similarity of genre features of music and classify it. 


# Flowchart or Activity Diagram
---------------------------------
![Activity Diagram](https://user-images.githubusercontent.com/59358909/85204021-5770c880-b331-11ea-8537-ddc68864a8dc.jpg)

