![💻 NFL_Helmet_Assignment](https://github.com/alexsowep/NFL-Helmet-Assignment/assets/102556708/b47967c5-37aa-4265-99da-9f158b0ab44d)

# NFL-Helmet-Assignment

### Description

A NFL Helmet Assignment Object Detection. Leveraging Tensorflow Model Zoo Pre-trained model [LINK](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md). The purpose of this project is to correctly identify individual helmets from both teams on a football field.

### Data

The data used for the project was taken from the NFL Health & Safety Kaggle competition. Training and testing labels are provided, though, currently the project manually labels images from data for training and testing. Competition is linked here: [LINK](https://www.kaggle.com/competitions/nfl-health-and-safety-helmet-assignment/data)

### Notes

* The notebook to this project was made with Google Colab. Running the notebook with Jupyter Notebook may run into dependenc issues.
* This project is currently a work in progress and requires extensive performance tuning and use of more powerful models (Detection is currently weak as shown below).
  ![WeakDetection](https://github.com/alexsowep/NFL-Helmet-Assignment/assets/102556708/a9c7e627-0db1-4bf9-bdaa-beef49445081)
* Solutions to this project have used multiple object tracking with DeepSort - Currently manualy labeling is being done.

### Credit

This TFOD course [LINK](https://github.com/nicknochnack/TFODCourse) provided very useful to the development of this project.
