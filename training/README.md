# Machine_learning_and_AI


# Plant Disease Prediction

## Problem statement

Plant disease affects the quality of fruits, vegetables and causes heavy loss in production. Present method is manual that involve by observing leaf. To overcome this problem our plant disease model is beneficial.
To build a CNN based model which can accurately detect plant disease. A solution which can evaluate images and alert the farmers about the presence of disease.

[Dataset is taken from this kaggle dataset](https://www.kaggle.com/arjuntejaswi/plant-village)

Dataset contain healthy and unhealthy plant leaf images. 
This dataset contain about 20K images of plant leaf images. The dataset contains 15 sub-directories of plant disease images. 

- Pepper__bell___Bacterial_spot
- Pepper__bell___healthy
- Potato___Early_blight
- Potato___Late_blight
- Potato___healthy
- Tomato_Bacterial_spot
- Tomato_Early_blight
- Tomato_Late_blight
- Tomato_Leaf_Mold
- Tomato_Septoria_leaf_spot
- Tomato_Spider_mites_Two_spotted_spider_mite
- Tomato__Target_Spot
- Tomato__Tomato_YellowLeaf__Curl_Virus
- Tomato__Tomato_mosaic_virus
- Tomato_healthy

From each class random 600 images are picked for model building.
To create train and test dataset run this script `create_train_test_folder.ipynb`
