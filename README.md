# Humpback-Whale-Identification

As a part of the Data Science workshop at the Open University of Israel we tackled the problem of [Humpback Whale Identification](https://www.kaggle.com/competitions/humpback-whale-identification/overview) on Kaggle.

The dataset presents many problems such as many classes (5005 classes), few images for each class (41% of the classes with only 1 image), 38% of the dataset is unlabeled (labeled as "new whale" which is a whale we haven't seen before), different shapes and color of an image (RGB or Grayscale) and many more.

In our solution we used EfficientNetV2_S, ArcFace Loss and YoloV7 in order to achieve 88.5% accuracy on the test data.

Images of what our model learned:
![image](https://github.com/amita1996/Humpback-Whale-Identification/assets/64536392/3690687b-d9c5-443b-8104-6e220e99c891)

The notebook might be too big to display on github. Please use one of the following links: [nbviewer link](https://nbviewer.org/github/amita1996/Humpback-Whale-Identification/blob/main/Humpback%20Whale%20Identification.ipynb) or [Colab link](https://drive.google.com/file/d/1omW67y9B6v8CGpfdej1UWuucLL5IPkIZ/view?usp=sharing)
