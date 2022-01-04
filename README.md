# Song-Emotion-Detector-Happy-Sad-
The main objective of this project is to create analyzer model on which all the songs will be trained and also increase the efficiency to achieve desired goal

download youtube_dl package
first made a links of all the songs links in .json file. With '1' labelled it to give Sad feeling and '0' as Happy feeling

then i ran the download audio.py to download alll audio(takes lot of time) and store the filename classifier file.
from there now with filnename file we preprocess the data(takes a lot of time) and it gets saved in a data(.json) file with a large size cause of the no. songs.

Now, we run the logger.py to know how much classifiers of all the songs are present in the data.json file. Then now we run the trainModel.py to train AI with the the songs. Run testmodel for getting the output ogf the test result rate of AI predictor.

run the mainGUI.py, put in the video file browse and put it and then open to check and then click analyse it will give answer depending on the percentage of 50 and above to be YES and 50 below to be NO.
