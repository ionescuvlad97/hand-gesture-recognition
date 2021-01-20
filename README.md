# Hand Gesture Recognition

Hand Gesture Recognition using Image Processing and Machine Learning.

## About <a name = "about"></a>

This project implement a basic hand gesture classification for a small dataset, using **OpenCV** for image processing and **Scikit-Learn** for machine learning. </br>
A *Histogram of Oriented Gradients* (***HoG***) approach is used to extract the form and texture features. Firstly, the images are resized and converted into gray space to reduce the dimensionality of the feature vectors. HoG is applied to the reshaped images. The features extracted after applying HoG are used for classification.</br>
For the classification are used two algorithms: ***KNN*** and ***Random Forest***. To find the best accuracy a ***Grid Search*** is performed. For KNN two parameters are varied: *the number of neighbors* and *the metric*. For Random Forest the varied parameter is *max depth*. The final accuracy is 80% for both algorithms.

## Usage <a name = "usage"></a>
You can download the project and run it in *Jupyter Notebook* or in *Google Colaboratory*. You can use other approach and other classification or clustering algorithms to increase the accuracy.
## Built Using <a name = "built_using"></a>
- [OpenCV](https://staging.opencv.org/) - *Image Processing*
- [Scikit-learn](https://scikit-learn.org/stable/) - *Machine Learning*
- [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) - *Data Visualization*
