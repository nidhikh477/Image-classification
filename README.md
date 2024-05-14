# Image-classification
In this data science and machine learning project, I have classified sports personalities. I have restricted classification to only 5 people,

Maria Sharapova
Serena Williams
Virat Kohli
Roger Federer
Lionel Messi
Technologies used in this project,
Python 3.8
Numpy and OpenCV for data cleaning
Matplotlib & Seaborn for data visualization
Sklearn for model building
Jupyter notebook, visual studio code and pycharm as IDE
Python flask for http server
HTML/CSS/Javascript for UI
Model Selection and Methodology
image
In this project, OpenCV haarcascade was used to detect face and two eyes. Wavelet transform was used to extract these features from the images. Finally after processing and cleaning the data, it was given as input to models. Various models were tried using GridSearchCV and Logistic Regression was found to give the best resutls with a score of 84.15%.


Above is the heatmap showing the results of Logistic regression on test data. For test images, Logistic regression was found to give a score of 95%. The model accuracy could be improved by using a bigger dataset. Also deep learning may give better results for image classificaion
