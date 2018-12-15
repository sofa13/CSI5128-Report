# The  Relationship  between  Energy  Barriers,  Fitting  and  Generalization

This is for anyone interested in following our ideas in the CSI5138 Report "The  Relationship  between  Energy  Barriers,  Fitting  and  Generalization".

Here we share the code we used to perform data augmentation and Gaussian noise. 

The code is based on the `data.py` file provided by [Garipov et al.](https://github.com/timgaripov/dnn-mode-connectivity)

In particular we made the following modifications to `data.py`.

- We added a `GaussianNoise` class to control the proportion of input images replaced with Gaussian noise for the training set.
- We commented out and uncommented the data augmentation transforms random flipping and random cropping when applicable.