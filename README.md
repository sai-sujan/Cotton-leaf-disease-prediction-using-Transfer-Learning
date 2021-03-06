# Cotton Leaf Disease Prediction Using Transfer Learning🌿

<p align="center">
  <img width="900" height="500" src="https://i.imgur.com/zxBiJCi.jpg">
</p>

## 📌 Introduction
This Deep Learning Web Application was created with Tensorflow-Keras and Transfer Learning, and it uses the INCEPTIONV3 Architecture to categorise photos of infected cotton leaves, fresh cotton leaves, diseased cotton plants, and fresh cotton plants. We used different Transfer Learning Architectures to train this Cotton Leaf Image Dataset during the process of generating a great model. On a batch size of 32, our model performs rather well over 20 epochs, with a Validation Accuracy of 0.96. This is a useful tool for utilising the capabilities of Machine Learning and Artificial Intelligence in Image Classification Problems .

## 🤖 **Benchmarks of Different Transfer Learning Architecture on our Dataset:**

**1. InceptionNetV3 Performance:**

<p align="center">
  <img width="600" height="300" src="https://i.imgur.com/wpVFSa2.png">
</p>

<p align="center">
  <img width="600" height="300" src="https://i.imgur.com/K08Qmvq.png">
</p>

`loss: 0.5233 - accuracy: 0.9487 - val_loss: 0.0012 - val_accuracy: 1.0000`

**2. RESNET50 Performance:**

<p align="center">
  <img width="600" height="300" src="https://i.imgur.com/ymq1dEJ.png">
</p>

<p align="center">
  <img width="600" height="300" src="https://i.imgur.com/ub0IZaU.png">
</p>

`loss: 0.7661 - accuracy: 0.7355 - val_loss: 0.5443 - val_accuracy: 0.7778`


**3. RESNET152V2 Performance:**

<p align="center">
  <img width="600" height="300" src="https://i.imgur.com/D9o9OjH.png">
</p>

<p align="center">
  <img width="600" height="300" src="https://i.imgur.com/UlmI9Uz.png">
</p>

`loss: 0.2298 - accuracy: 0.9800 - val_loss: 1.8554e-05 - val_accuracy: 1.0000` 

***As we have seen that RESNET152V2 is Performing best in comparasion to all other Transfer Learning Architecture,But when compare to speed of giving results INCEPTIONV3 is faster than RESNET152V2. So we have picked up INCEPTIONV3 Architecture and Trained Our Model over it!!*** 

## Demo
Link: [https://share.streamlit.io/sai-sujan/cotton-leaf-disease-prediction/main/main.py](https://share.streamlit.io/sai-sujan/cotton-leaf-disease-prediction/main/main.py)

[![](https://i.imgur.com/d5SUSBb.jpg)](https://share.streamlit.io/sai-sujan/cotton-leaf-disease-prediction/main/main.py)

[![](https://i.imgur.com/6pVV50n.jpg)](https://share.streamlit.io/sai-sujan/cotton-leaf-disease-prediction/main/main.py)

## 🎯 Purpose of the Project

India is the world's largest producer of cotton. The US Department of Agriculture (USDA) estimates that India will produce 29 million bales of cotton in the 2019-20 season, up from 26 million bales the previous year. According to the latest data, India is on track to overtake China, which is forecasting 27.75 million bales for the same season. Despite these outstanding figures, however, the productivity per hectare is shockingly low. Cotton production in India is gradually declining year after year due to major cotton illnesses that have a significant impact on production. Common diseases such as insect attack, charcol rot, and others are wreaking havoc on their plantations. As a result, many cotton producers see a significant decline in productivity and income. The problem will be remedied if farmers are informed about infected and diseased plants at an early stage of their growth, allowing them to employ pesticides and other medicinal equipment to saturate plants with medicine and protect their crops from illness at an early stage of production. ***Because this project will assist farmers in identifying which cotton plants are fresh and which are diseased by simply uploading photographs of the cotton plants to the web app, this project will assist farmers in identifying which cotton plants are fresh and which are diseased. On a production level, this online software might be turned into an android app that allows farmers to snap a picture of their cotton plant and promptly receive results. ***


## 🏁 Technology Stack

* [Streamlit](https://www.streamlit.io/)
* [Tensorflow 2.x](https://www.tensorflow.org/)
* [Keras-Transfer-Learning](https://keras.io/api/applications/)

## 🏃‍♂️ Local Installation

1. Drop a ⭐ on the Github Repository. 
2. Clone the Repo by going to your local Git Client and pushing in the command: 

```sh
git clone https://github.com/sai-sujan/Cotton-leaf-disease-prediction.git
```
3. Install the Packages: 
```sh
pip install -r requirements.txt
```

## Frontend Using Streamlit

<p align="center">
  <img  src="Utils/streamlit.png">
</p>

1.Run your Streamlit App

```sh
streamlit run {Name_of_Your_Streamlit_App}.py

```

For this Project Run this CMD:

`streamlit run main.py`


