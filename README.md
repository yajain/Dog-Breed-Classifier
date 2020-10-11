# dogapp

PyTorch model to look at an image of a dog and identify it's breed using a pre-trained resnet50 architecture.

A fun addition at the end is that it can look at a human picture and tell what breed of dog does the human most closely resemble. 

You can import your own images to the folder titled images and change the name of the file path at the appropriate location at the code (at the end) to identify which breed of dog you most closely resemble.

# dependancies

1. PyTorch
2. Python 3.x
3. numpy, matplotlib

Step 0: Import Datasets
Make sure that you've downloaded the required human and dog datasets. The datasets can be found in the dog_app notebooks:


Download the dog dataset. Unzip the folder and place it in this project's home directory, at the location /dog_images.

Download the human dataset. Unzip the folder and place it in the home directory, at location /lfw.

Note: If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

In the code cell below, we save the file paths for both the human (LFW) dataset and dog dataset in the numpy arrays human_files and dog_files.

# details
Dataset is in the data folder

Accuracy - 83%

Uses CUDA & GPU to speed up training. You need to have access to a GPU to use the cuda feature
