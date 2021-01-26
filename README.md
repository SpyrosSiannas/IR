# Movie Search Engine using Elasticsearch and Machine Learning Methods
## About
Information retrieval project that utilizes elasticsearch, supervised and unsupervised machine learning to retrieve search results based on user movie ratings.

*Developped by: Siannas Spyros, Papanikolaou Athos*

## 1. Installation
Install [python](www.python.org) **Note: Tensorflow only works for versions <=3.8 (25/01/2021)**
### 1.1 Install the following Python Modules
- [tensorflow](https://www.tensorflow.org/install/)
- [keras](https://pypi.org/project/Keras/)
- [pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)
- [elasticsearch for python](https://pypi.org/project/elasticsearch/)
- [sklearn](https://scikit-learn.org/stable/install.html)
- [gensim](https://pypi.org/project/gensim/)

### 1.2 Elasticsearch
- Download and extract [elasticsearch](https://www.elastic.co/downloads/elasticsearch) to your `C:\` directory
- Open a command prompt in the directory `C:\\(elasticsearch folder name)\bin`
- Execute:

      elasticsearch.bat

## 2. Set up and run
Download the latest release and extract it in a directory
### 2.1 Set up the configuration file
<img align="right" src="https://i.imgur.com/FcA5ez3.png">

Open `src/cfg` and specify the configuration parameters
- Elasticsearch port and host
- Limit on printed results
- Neural network training parameters
- Mapping is a dictionary that maps genres to indices, leave it empty


### 2.2 Elasticsearch
Make sure elasticsearch is running in the background (follow the method in paragraph [1.2 Elasticsearch](#12-elasticsearch))


### 2.3 Run the program
You can either run the program from an IDE or open a command line in the project folder and execute the command:

    python main.py

You can follow the instructions in the console from now on!
![ui](https://i.imgur.com/BOhpBXT.png)
