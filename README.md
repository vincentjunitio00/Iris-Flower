# Iris-Flower
The dataset is taken from Iris Flower Dataset at Kaggle. Link: https://www.kaggle.com/arshid/iris-flower-dataset

## What is this dataset about? ##
This dataset is used to do a multi-class classification (3 classes). It only contains 150 records.
The attributes in the set are:
* Petal Length: the length of the petal - modified leaf which surround the reproductive parts of a flower.
* Petal Width: the width of the petal.
* Sepal Length: the length of the sepal - the outermost part of a flower which encloses its developing reproductive structures.
* Sepal Width: the width of the sepal.
* Species: the species of the flower (Iris setosa, Iris versicolor or Iris virginica)

## Parts of a Flower ##
<img src="https://images.squarespace-cdn.com/content/v1/54a0bf64e4b07c077784c627/1444142936251-05SPCNHMXG4L0QOZZ8QU/ke17ZwdGBToddI8pDm48kNIowuOGXZvvQmNGncAN1E97gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QHyNOqBUUEtDDsRWrJLTmaUzSiviepfuOufnJa7SEDbr9Wn2yvYHikg245dY2aeryt-cseUh_XKtvQuJeYxOh/image-asset.jpeg?format=1000w" width="500" height="500">
Image Source: https://www.mathwizurd.com/bio/2015/10/6/angiosperms-and-the-structure-of-a-flower

## What should we do? ##
I split this dataset into training set and test set. I am going to use a simple machine learning technique (Support Vector Machine) with no hyperparameter tuning so I do not use a validation set here.

Since the dataset is small (150 records), I use 141 records as the training set and 9 records as the test set.

If you are interested in trying a different machine learning technique such as Random Forest, K-Nearest Neighbours and more, feel free to tweak my code. You can also play around the split number so you can see how learning from such an amount of training set may affect your test set.

:)) Hope you enjoy it!
