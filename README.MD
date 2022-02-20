# README

Skin cancer is a serious condition. Different strategies have been developed to distinguish between various forms of skin cancer. Visualizing with clinical screening by dermoscopic analysis can detect it in its early phases. A common goal is to detect a skin lesion automatically. Small blood vessels, a thicker patch, ulceration, and bleeding are all signs of skin cancer. Skin cancer can be spotted using polarised light and a skin magnifier, and it can be diagnosed using a deep learning classifier with data augmentation and weights. The VGG-16 and Resnet50 classifiers are implemented in this report with weights assigned to the classes because of data imbalance between each classes, and the pictures were augmented before training the model to redict 7 different types of cancer clases.

## Steps to run the report.

1. Create & set project folder (Skin cancer - with content folder in it) as you current directory.
2. Unzip the data and put all the files inside content folder.
3. Install all python packages mentioned inside the start of the notebook.
(Use pip install "package name" - to install the python packages)
	tensorflow
	sklearn
	PIL
	matplot
	seaborn
	glob
	numpy
	pandas


**Folder structure**

'Skin Cancer' folder
   |-   ipynb file here
   |-	'content' folder
	   |-	metadata files.csv
	   |-   Image data in the form of the two folders

*Note: you can remove comments form the Image data generator to train the model and produce result based on augmented image data.