# Crop-Disease-Detection-System

Crop Disease is necessary for every farmer so we are created Crop disease detection using Deep learning. In which we are using convolutional Neural Network for classifying Leaf images into 39 Different Categories. The Convolutional Neural Code build in Pytorch Framework. For Training we are using Plant village dataset.

# How to run this project - 

[1] You must have Python3.8 installed in your machine.

[2] Create a Python Virtual Environment
>•	python -m venv venv

[3] Activate Virtual Environment by
>•	venv\Scripts\activate.ps1

[4] Install all the dependencies using below command
>•	pip install -r requirements.txt

[5] Go to Folder Flask Deployed App
>•	Download the pre-trained model file plant_disease_model_1.pt from Here
>
>•	Add the downloaded file in Flask Deployed App folder.

 [6] Run the Flask app using below command 
>•	python3 app.py

# Testing Images-
If you do not have leaf images then you can use test images located in test_images folder.
Each image has its corresponding disease name, so you can verify whether the model is working perfectly or not



# Snippet of web app-

![image](https://github.com/falgunirawat13/Crop-Disease-Prediction-System/assets/115785063/3169cbed-e1ad-4f60-96b2-5c99e4f59fc5)
![image](https://github.com/falgunirawat13/Crop-Disease-Prediction-System/assets/115785063/ea0374cb-6823-4fcf-bbc4-72d7910d0086)
