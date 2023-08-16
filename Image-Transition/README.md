# Image-Transition

● The code is being presented in the form of a Jupyter notebook
and images which are taken as input to the code should be in the
directory where this .ipynb file is saved in the “Scene” named
folder.

● There is a total of 8 transition images that have been taken as an
output from the code but due to less number of training images
and the images being rainy/cloudy which are somewhat dark
which caused the darkness in the output images as well.

● We get the final intermediate transition image in the output in the
dimension of 512X512.

● There are total 3 .ipynb files where
  1. Image transition without training. ipynb->this is the image
     transition between 2 images but without training.
  2. Image transition with training.ipynb-> this is the image
     transition between 2 images but the model is initially trained with
     a given dataset of 84 images of weather due to which we get a
     somewhat more accurate intermediate image as output than the
     previous case.
  3. Image transition with training with large data which only
     contains rainy pics.ipynb->this is the image transition between
     2 images but the model is initially trained with a given dataset of
     430 images of rainy weather conditions which are taken from the
     dataset which are present online. The transition image is
     somewhat more accurate but as most of the trained images
     being dark so even the intermediate images are also being dark.

● We have taken a few videos from the ‘drive and learn’ website
and snaps of the video are taken manually every 10 sec for a
total of 3 videos which are sunny, rainy, and cloudy images that
are stored in the ‘Frames’ folder.
