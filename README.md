# Skin Lesion Analyzer

### What is this all about?
The aim of this project is to detect **skin lesions** using a deep learning model. This project is a part of the ongoing **[#PoweredByTF 2.0 Challenge! ](https://tensorflow.devpost.com/)**. As the challenge is based on TF2.0, our aim is to build something in order to showcase:
* The ease of using TF2.0
* The power and simplicity of **Keras**
* The exceptional **tflite** framweork

### Introduction
Any type of cancer is somehow deeply dangerous if not deadly. To see how bad the sitaution is, let us look at some of the stats given by the [skin cncer organisation](https://www.skincancer.org/skin-cancer-information/):
* One in five Americans will develop skin cancer by the age of 70
* Actinic keratosis is the most common precancer; it affects more than 58 million Americans
* The annual cost of treating skin cancers in the U.S. is estimated at $8.1 billion: about $4.8 billion for nonmelanoma skin cancers and $3.3 billion for melanoma.
* Skin cancer represents approximately 2 to 4 percent of all cancers in Asians
* Skin cancer represents 4 to 5 percent of all cancers in Hispanics
* Skin cancer represents 1 to 2 percent of all cancers in blacks

### Problem
Analyzing cancers isn't an easy task. It requires intensive examining. More than 50% of lesions are confirmed through histopathology (histo), the ground truth for the rest of the cases is either follow-up examination (follow_up), expert consensus (consensus), or confirmation by in-vivo confocal microscopy (confocal). The lack of experts(radiologists) has always been a bottleneck. Now there are three things that we have to consider here:
* Given that the number of experts are less, how can we make them more efficient? Can we aid them using state of the art machine learning techniques? If yes, how?
* Training of neural networks for automated diagnosis of pigmented skin lesions is hampered by the small size and lack of diversity of available dataset of dermatoscopic images. Labelled data in healthcare is another bottleneck. With the available limited data, how much can we do?

As a Machine Learning Engineer, if we can't help the doctors and ultimately society, then what are we good at? Healthcare is a complicated field and using Machine Learning in this field has its own *advantages* and *disadvantages*. There is a limit to which we can do things with ML in healthcare. In conclusion, this matters!

### Dataset
The dataset is a part of [Kaggle Datasets](https://www.kaggle.com/kmader/skin-cancer-mnist-ham10000). A big thank you to **Kevin Mader** for uploading this dataset to kaggle.  

