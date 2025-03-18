# ⭐ Plant-Disease-Detection

Plant Disease is necessary for every farmer, so we have created Plant Disease Detection using Deep Learning. We are using a Convolutional Neural Network (CNN) for classifying leaf images into 39 different categories. The Convolutional Neural Network is built using the PyTorch framework. For training, we are using the PlantVillage dataset. The dataset link is in my blog section.

## 🖼️ Screenshots


## ⭐ Run Project in your Machine

You must have Python 3.8 installed on your machine.

1.  Create a Python Virtual Environment & Activate Virtual Environment: [Link to Virtual Environment Instructions](https://docs.python.org/3/tutorial/venv.html)
2.  Install all the dependencies using the command: `pip install -r requirements.txt`
3.  Go to the `Flask Deployed App` folder.
4.  Download the pre-trained model file `plant_disease_model_1.pt` from [here](https://drive.google.com/file/d/1moSLVuAevmCgSiBsYWbi1ueJIXXRzlrG/view?usp=sharing).
5.  Add the downloaded file to the `Flask Deployed App` folder.
6.  Run the Flask app using the command: `python3 app.py`
7.  You can also use the downloaded file in the `Model` section and play with it using Jupyter Notebook.

## ⭐ Contribution (Open Source)

This project is now open source. All developers who are interested can contribute to this project. You can improve the UI, make the Deep Learning model more powerful, or add informative markdown files in sections.

If you change the Deep Learning model, make sure you upload the updated markdown file (.md), .pdf, and .ipynb in the particular section. Make sure your code is working and does not have any errors.

You have to fork this project and then make a pull request after your testing is successful.

How to make a pull request: [https://opensource.com/article/19/7/create-pull-request-github](https://opensource.com/article/19/7/create-pull-request-github)

## ⭐ Testing Images

If you do not have leaf images, you can use the test images located in the `test_images` folder. Each image has its corresponding disease name, so you can verify whether the model is working perfectly or not.
