# Identifying Parisitized Malaria Cells with the LeNet Model (Convolutional Neural Networks)
___
![My Skills](https://skillicons.dev/icons?i=py,tensorflow,git,github)](https://skillicons.dev)

**This practice project focuses on building, training & optimizing a convolutional neural network with the LeNet model architecture in order to find malaria infected cells using microscopic images.** The LeNet model is a simple convolutional neural network architecture originally developed in 1989. We will use this model architecture along with the ready to use TensorFlow datasets malaria dataset in order to make a binary prediction as to whether a particular cell is infected based on a threshold value of 0.5 where a prediction < 0.5 implies that the cell is not infected & vice versa.

Images have been prepared using the microscopic examination of blood smears (considered the gold standard for malaria diagnosis). A small amount of the patient's blood is smeared on a glass slide, stained with special dyes, and examined under a microscope. Images have been classified as parasitized/uninfected by trained laboratory technicians who examine the species for the presence of the malaria parasite.

## 🛠️ Getting Started
___
###### Fork & Clone
Fork the repo using the fork button in the top right of the screen. When the fork has been created, get the .git URL from your fork.

Create a new folder on your local machine (my_news_api) & clone to your local machine from a terminal open to this folder using the fork URL & the below command.
`git clone <URL_for_your_fork.git>`

Open the folder in your IDE of choice using the required Jupyter notebook extension if required.

**VENV**
This project uses a python virtual environment for it's dependencies. Setup & activate a new virtual environment by opening a new termina in the project directory & running the following:

1. `python -m venv venv`
2. Powershell: `.\.venv\Scripts\activate`
   Bash: `source venv/bin/activate`

Add the created virtual environment directory to your .gitignore file. 

###### Dependencies
Install required dependencies listed in `requirements.txt` using `pip install -r requirements.txt`

## 🔢 Versions
___
| **Tech**   | **Version** | **Command** |
| ---------- | ----------- | ----------- |
| TensorFlow |             |             |
| Numpy      |             |             |
| Matplotlib |             |             |
| TensorFlow Datasets           |             |             |
