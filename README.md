
# Fruits and Vegetable Recognizaiton- CNN,Transfer Learning


## 📝 Overview
Trained a multiClass classification Convolution neural network by TransferLearning using MobileNetV2
with imagenet weights.Which takes image data and predicts the name of fruits and vegetables.Trained on 
GoogleColab.

## 🧰 Technical Aspects

- Trained on GoogleColab.
- Image Data preprocessing.
- Data Visualization and Exploratory Data Analysis.
- Image Data Normalization and Scaling.
- Used image_dataset_from_directory for batch creation.
- Created augmented data configuration inside Sequential model layer.
- Trained the model in FunctionalApi config 
  by transferLearning using MobileNetV2 with imagenet weights as base model.
- Also added multiple GlobalAveragePooling2D layers,Flatten and Dense layers on top
  of based model for output.
- Retrained the model after hyperparameter tuning with baselayers of pretrained model as trainable and
  acquired better accuracy.
- Tested the model on custom data.  

## ⏳ DataSet
https://www.kaggle.com/kritikseth/fruit-and-vegetable-image-recognition


## 🖥️ Installation
### 🛠️ Requirement

* Tensorflow 2
* Keras
* Numpy
* Matlplotlib
* Seaborn




    
## ⚙️ Tech Stack
<p float="left">
<img src="https://miro.medium.com/max/1184/0*zKRz1UgqpOZ4bvuA" width="20%" >
<img src="https://john.soban.ski/images/Fast_And_Easy_Regression_With_Tensorflow_Part_2/00_Tf_Keras_Logo.png" width="30%" >
<img src="https://i2.wp.com/softwareengineeringdaily.com/wp-content/uploads/2016/09/scikit-learn-logo.png?resize=566%2C202&ssl=1" width="40%" >
<img src="https://joblib.readthedocs.io/en/latest/_static/joblib_logo.svg" width="20%" >
<img src="https://fiverr-res.cloudinary.com/images/q_auto,f_auto/gigs/187550926/original/cde47296f9d02346b6561eee753741d7272bfce6/do-data-analysis-in-python-using-numpy-pandas-matplotlib-seaborn.jpg" width="70%" >

</p>


