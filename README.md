# GAN_Anime

This repo does not include the dataset. The dataset can be found using this link: https://www.kaggle.com/datasets/prasoonkottarathil/gananime-lite

To execute the code, first download the anime faces dataset mentioned earlier and place it in the directory ./images/class1/.

where the `class1` folder will contain all the image datasets.

### File

`GAN.ipynb`: Python file that includes the construction of generator and discriminator for DCGAN, note the training device is Metal Performance Shaders (MPS) for GPU training acceleration. If you are not using a Apple silicon or AMD GPUs, please use cuda.