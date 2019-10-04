# Face Recognition using KNN

k-Nearest Neighbours or KNNs, is a method that can be used both for classification and regression tasks.
The classfication accuracy of kNN largely depend on the value of 'k' and the distance metric used for classification. 

Euclidean distance was used as the distance metric for this case.

In **face_detection.py**, CascadeClassifier() from OpenCV (https://opencv.org) was used to detect and enclose faces with a bounding boxes

In **face_recognition.py**, the frames were first converted into gray-scale, and the faces present in it were detected by CascadeClassifier() just like in **face_detection.py**.
Then the person in the image was recognised with the help of kNN. Here, the value of **k** is taken to be **5**.


**Links :**

1 . https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm

2 . https://github.com/div3125/k-nearest-neighbors

3 . https://github.com/tarunkolla/KNN-Classifier
