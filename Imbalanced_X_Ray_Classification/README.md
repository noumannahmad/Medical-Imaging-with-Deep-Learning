# Chest X-Ray Medical Diagnosis with Deep Learning using Imbalanced Dataset

We will be using the ChestX-ray8 dataset which contains 108,948 frontal-view X-ray images of 32,717 unique patients.

Each image in the data set contains multiple text-mined labels identifying 14 different pathological conditions.
These in turn can be used by physicians to diagnose 8 different diseases.
We will use this data to develop a single model that will provide binary classification predictions for each of the 14 labeled pathologies.
In other words it will predict 'positive' or 'negative' for each of the pathologies.
You can download the entire dataset for free here.

We have provided a ~1000 image subset of the images for you.
The dataset includes a CSV file that provides the labels for each X-ray.

To make your job a bit easier, we have processed the labels for our small sample and generated three new files to get you started. These three files are:

train-small.csv: 875 images from our dataset to be used for training.
valid-small.csv: 109 images from our dataset to be used for validation.
test.csv: 420 images from our dataset to be used for testing.
This dataset has been annotated by consensus among four different radiologists for 5 of our 14 pathologies:

Consolidation
Edema
Effusion
Cardiomegaly
Atelectasis

![x-rays-1](https://user-images.githubusercontent.com/43134572/122554715-c7a05000-d052-11eb-83ec-2f5fc330a352.png)

![xray-2](https://user-images.githubusercontent.com/43134572/122554742-ce2ec780-d052-11eb-8620-3e3d815a9b22.png)
