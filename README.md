# CNN-for-IDC
This Notebook will help predict Invasive Ductal Carcinoma(IDC) from Breast Histopathology Image patches.

### Getting Started
You will first need to download the Breast Histopathology Images Data Set to run this Jupyter Notebook.
The data can be found [here](https://www.kaggle.com/paultimothymooney/breast-histopathology-images).
Unzip and put all the data inside a folder named 'data', in the same file path Directory as the Jupyter Notebook, and you are good to go. I will create a folder named 'data', and leave it empty (well github won't let me do that so I will have a redundant file in the folder), to help you set it up easily.

### Installing
I haven't really used any exotic libraries, so you wouldn't need to install anything other than the basics.
```
numpy                 cv2                  PIL
pandas                fnmatch              sklearn
matplotlib            tqdm                 imblearn
seaborn               glob                 keras
```

### Other Details
The model weights for the trained Convolutional Neural Network can be found in 'model_weights' folder under the name 'best-mdl_cp_23.h5'. 


### Final Note
I have done my best to help you get started with my Jupyter Notebook. If I missed something, I apologies for my clumsiness and hope you can figure it out, or just contact me and I'll be more than happy to help you out. Anyway, have fun!!!

Let's get started then...
