# Download Dataset & Tips

You can download the dataset used in my notebook from kaggle in the link provided below:
https://www.kaggle.com/fushenggg/3-class-track-direction-dataset

Unzip the file, it will contain 2 folders - a) TrackImage0 and b)rename(example)

a) TrackImage0
Double click the 'TrackImage0' folder, you will see another 'TrackImage0' folder. Drag it into your current working directory
Download the ipynb file (3 Direction Track Image) and make the following changes to the directory

To view your CWD
import os
os.getcwd()

Mine is 'C:\\Users\\kansh\\Desktop\\FYP'

There are TWO WAYS to LOAD the folder from directory path

1. filenames = os.listdir('C:\\Users\\kansh\\Desktop\\FYP\\TrackImage0\\data')
       OR
2. filenames = os.listdir('TrackImage0\\data') 

Once you finish specifying all directory path for train_generators etc, you can run the whole file and create your first CNN model

b) rename(example)
This folder contains example images in the 'Rename all files' notebook tutorial. 
Double click the folder, drag the 'image' folder into your current working directory.
You can run the tutorial notebook. 
To test this notebook on the actual tub of collected images:
1. Copy some images of the same directory and paste in a new folder(anyname) in your cwd
2. Change the dst, src and dst in the notebook before running the cell. 
   The 1st line - dst contains the filename you want to name as.
   The 2nd and 3rd line - src and dst contains the cwd path where your file is at
3. Check if your images have been renamed in running order.
