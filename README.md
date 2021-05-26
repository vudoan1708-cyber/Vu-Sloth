# Description
The project is about implementing a GAN (DCGAN, StyleGAN) network to blend facial features of mine and sloth's

# Google Colab links
[DCGAN] (https://colab.research.google.com/drive/1vNZ1swbEwyLJlvbV0_WDYcRYHQ1BfV8O?usp=sharing) <br />
[StyleGAN2] (https://colab.research.google.com/drive/1Bitt3DRPTAU8B8HrA4XYfsCnHk795Bd2?usp=sharing)

# Prerequisites based on Google Colab
Python version: 3.7.10 <br />
Tensforflow versions depend on which network is used
## DCGAN
Tensorflow version: 2.4.1
## StyleGAN2
Tensorflow version: 1.15.2

# Use Case
Make sure you have got all the dependencies installed by doing
```bash
pip install -r requirements.txt
```
as well as installing the prerequisites mentioned above <br />

You will also need to create a folder named "my_new_dataset" inside the "dataset" folder, so that when the code processes the images, duplicate them and relocate those to a new folder, you won't get an error

# Caution
Since the files (dataset + training model checkpoints and the result images) are too big. The download time may take a long while. Please be patient! Thank you!!! <br />
Also, the training models were too large even for Github Large File Storage (LFS) to handle. Therefore, some other training and image files would be omitted for the sake of uploading and downloading them