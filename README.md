# Project4

okay working on getting the training and test data csv's from https://www.kaggle.com/c/facial-keypoints-detection/data uploaded, but they're large files so until that works just go there and download local.
needs Git Large File Storage to imports into git, as the training is over 50 mb


So order of operations, take the training data out of the training/ file, put an unzipped copy into the data folder, and then reference the data folder not the training folder as its locations, keeps the training csv clean
Same goes for test, take it out of test, add it to demo and work from there.



There are 4 walkthrus that are good and what we want to do, the first is this one, which we already went over:
https://towardsdatascience.com/implementing-snapchat-like-filters-using-deep-learning-13551940b174

tried replicating his code, its 3 years out of date and the corresponding py and python files are:
read_data_face_detection.py
read_data_face_detection.ipynb
training_face_detection.py
training_face_detection.ipynb
face_detect_demo.ipynb
face_detect_demp.py


(Will put these in a directory of there own)

Second:
this is located at https://towardsdatascience.com/creating-a-snapchat-style-filter-with-python-b42ecfd2ff54, its from this year and uses live-capture

Third:
Article is https://towardsdatascience.com/how-to-create-real-time-face-detector-ff0e1f81925f, its good and uses live capture, everything is in ipynb files
those are located here https://gitlab.com/Winston-90/me_not_me_detector/-/tree/main/

I think we should do this one for each of us, it will train our model to recognize us as individuals, so on presentation day it will be 'attuned' for the lack of a better word to our mugs.
me_not_me.ipynb

everything from his in a jupyter lab 

Fourth:
Is her's, article here, https://medium.com/analytics-vidhya/creating-snapchat-like-filters-from-scratch-using-computer-vision-techniques-6374cde6a7db
github here: https://github.com/shyaa23/Snapchat-like-Filters-Using-Computer-Vision-Techniques

Again live, and worth looking at, cnn and number of layers


What Im working on right now is this, turns the same base of 2,140 images with all params of 15 faces into something with like 5 million params, working on goggle colab to get it to work





