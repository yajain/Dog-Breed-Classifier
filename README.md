# dogapp

PyTorch model to look at an image of a dog and identify it's breed using a pre-trained resnet50 architecture.

A fun addition at the end is that it can look at a human picture and tell what breed of dog does the human most closely resemble. 

You can import your own images to the folder titled images and change the name of the file path at the appropriate location at the code (at the end) to identify which breed of dog you most closely resemble.

# dependancies

1. PyTorch
2. Python 3.x
3. numpy, matplotlib

# datasets

The datasets can be found in my google drive. Here is a link to the zipped datasets:

https://drive.google.com/file/d/13gl64ZPwOqyN2-81htbVVwYcVN-tY5hs/view?usp=sharing      (human images)

https://drive.google.com/file/d/1ZP5wqJChNOXZgaPpt4ggJnYD5W9-Y9TS/view?usp=sharing      (dog images)

You will have to appropriately change the path of the datasets in the notebook.

# details
Dataset is in the data folder

Accuracy - 83%

Uses CUDA & GPU to speed up training. You need to have access to a GPU to use the cuda feature
