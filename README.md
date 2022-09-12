# Project Name : Melonama Detection Assignment
> Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The project is being submitted as partial fulfilment of Advanced Certificate in Machine Learning and Deeping Learning course conducted jointly by IIIT, Bangalore and Upgrad.
- Goal is to To build a CNN based model which can accurately detect melanoma.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Intial model was overfitting. Difference between train and validation accuracy was very high. The train accuracy was 88% and the validation accuracy wass only 54%
- Augmentation strategy was used to rectify the problem. There has been a considerable improvement now as compared to the previous model the model overfitting was handled, but the model performance was not so good only 60.7% train and 54.6% validation accuracy.
- There was high class imbalance in the Model. Seborrheic keratosis had the least number(77) of samples.Pigmented benign keratosis had the highest number(462) of samples.
- Class imbalance problem was rectified and model was retrained. After this the overfitting problem was removed. train accuracy 89.8% and validation accuracy 79.6%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python, Pandas, Numpy, Matplotlib ,Seaborn , TensorFlow , Keras , Glob
- Google Colab with GPU

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by IIIT, Bangalore and Upgrad, Bangalore..
- References if any...
- Python Documentation
- Upgrad Study Material
- https://www.tensorflow.org/tutorials/load_data/images


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
