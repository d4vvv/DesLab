# Design Laboratory - JetBot in a labyrinth

Authors: Aleksandra Macura & Kacper Godula

[Video presentation](https://youtu.be/fjIZXKG-1Q0)


As a Design Labory project, we decided to teach JetBot how to go through a labyrinth with prepared signs.
We used the method called transfer learning to retrain the Alexnet network with photos of circles, squares, arrows as well as free and blocked space.

It reacts in the following way:
* red circle - go right
* green square - stop 
* blue arrow - go left 
* free space - go forward
* blocked space - stop

Whole project is based on Jupiter Notebooks:
* data_collection.ipynb
* train_model.ipynb
* figures_recognition.ipynb

As it can be seen in the video, our goal is fulfilled - the robot reacts properly to the symbols that it sees using camera. Unfortunately there was a hardware problem  - callibration of the wheels. Because of that in most attempts the robot didn't go in the straight line far enough to see the next symbol.




