# Reproducibility-challenge-StarGAN-v
In this study, we undertook the reproducibility challenge for StarGAN v2, a state-of-the-art model
designed for image synthesis [1]. Our objective was to evaluate the consistency of the results presented
in the 2020 article, "StarGAN v2: Diverse Image Synthesis for Multiple Domains." We explored
cutting-edge models and examined how they can build upon previous methods if proven robust.
Our investigation revealed that the results reported in the original paper proposing StarGAN v2 are
relatively easily reproducible, solidifying its status as an outstanding model for multi-domain imageto-image translation. We successfully reproduced several experiments and obtained comparable
results through quantitative evaluation.

## Practical information
Dependencies to be installed for the paper code:
-torch
-torchvision
-opencv-python
-ffmpeg-python
-scikit-image
-scipy
-pillow version 7.0.0 
-tqdm version 4.43.0 
-munch version 2.5.0

In the attached notebooks, one for each experiment run, since it clones a specific Github branch created for each test, we have set everything up to run the code provided by the paper in its original form (entitled Stargan) and with the modifications made by us. 

StarGan.ipynb -> original paper code we used to replicate their results
leakyReLU__StarGan.ipynb -> experiment where we change hyperparameters of leakyRELU to 0.1 from 0.2
ELU__StarGan.ipynb -> Changing the non-linear activation function from leakyReLU to ELU with the default hyperparameter value of 1.0.
ELU0_5__StarGan.ipynb -> Changing the non-linear activation function from leakyReLU to ELU with the hyperparameter value of 0.5
