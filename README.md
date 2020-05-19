# MUST READ #

# *All notebooks, saved models and dataset folders must be inside your CWD

# Download Dataset & Saved Model
https://www.kaggle.com/fushenggg/3-class-track-direction-dataset

*Contains catdogcar1.hdf5 file to load model (Saves time from training)

Unzip the file, it will contain 2 folders - a) TrackImage0 and b)rename(example)

a) TrackImage0

Double click the 'TrackImage0' folder, you will see another 'TrackImage0' folder. Drag it into your CWD

b) rename(example)

This folder contains example images in the 'Rename all files' notebook tutorial. 

Double click the folder, drag the 'image' folder into your CWD.

You can run the tutorial notebook. 

To test this notebook on the actual tub of collected images:

1. Copy some images of the same directory and paste in a new folder(anyname) in your cwd

2. Change the dst, src and dst in the notebook before running the cell. 

   The 1st line - dst contains the filename you want to name as.
   The 2nd and 3rd line - src and dst contains the cwd path where your file is at
   
3. Check if your images have been renamed in running order.

Download the ipynb files and place in CWD

Drag the saved model and place in CWD 

# Running the notebook 
1. Check where your CWD is located at

To view your CWD import os os.getcwd()

Mine is 'C:\Users\kansh\Desktop\FYP'

2. Loading of folder from CWD (Changes to make)

Windows uses "\\" & Linux uses "//" for directory path

3. Ensure all directory path for train_generators are specified as well

# There are TWO WAYS to LOAD the folder from directory path
1. filenames = os.listdir('C:\\Users\\kansh\\Desktop\\FYP\\TrackImage0\\data\\'

2. filenames = os.listdir('TrackImage0\\data')



