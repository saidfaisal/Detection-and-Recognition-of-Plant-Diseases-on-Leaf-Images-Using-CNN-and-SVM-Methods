---
Platforms: Python + PyQt5
Author: saidfaisal
---

# Detection and Recognition of Plant Diseases on Leaf Images Using CNN and SVM Methods
Final project for fulfillment of the requirements for the degree of Sarjana Komputer (S.Kom).

## Overview
Tomato plants are very susceptible to diseases, tomato plant diseases can be known from the spots on the leaves. This disease can be recognized because it has a unique color and texture. But visual recognition has a disadvantage that is difficult to recognize the similarity between one type of disease with another disease so that the impact on the inaccuracy of the disease identified.

In this study, a system was built to determine disease and provide information in the form of treatment solutions to prevent or treat diseases that attack tomato leaves through digital image identification using supervised classification. The image that will be identified earlier goes through the process of RGB (Red Green Blue) color transformation to HSV (Hue Saturation Value), HSV (Hue Saturation Value) to Grayscale, and the GLCM (Gray Level Co-occurrence Matrix) texture feature extraction process. Texture feature extraction results are classified with SVM (Support Vector Machine) and CNN (Convolutional Neural Network) to determine the disease suffered by tomato leaves.

The test was carried out with 200 sample images of tomato leaves, 160 images as training data and 40 images as test data. The test results show the CNN method has an average percentage accuracy of 97.5%, precision 95.45%, recall 95% and error 5%. Whereas SVM produces an average accuracy of 95%, precision 90.83%, recall 90% and error 10%. From the test results, it can be stated that in this study CNN is a better classifier than SVM.

## Links (Research Purpose Only)
* https://www.dropbox.com/s/tva49skiutv2u75/Program%20-%20Tugas%20Akhir%20%28password%20needed%29.zip?dl=0 - (Project - Password Needed)
* https://www.dropbox.com/s/xrrhyjh9e9oh96w/journal.pdf?dl=0 - (Journal)

## Screenshots
![cnn-program](https://user-images.githubusercontent.com/28735519/66263034-7b799180-e816-11e9-9e29-ebb91fa47a0c.gif) ![svm-program](https://user-images.githubusercontent.com/28735519/66263035-8502f980-e816-11e9-9d7f-225f7c42af72.gif)
![Hasil](https://user-images.githubusercontent.com/28735519/66263037-8d5b3480-e816-11e9-82ef-30e9bb146f84.PNG)



