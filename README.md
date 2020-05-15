# Discovering-Cross-Domain-Relations-for-Unpaired-Image-to-Image-Translation-Using-Generative-Adversar
-Using the Disco GAN network, obtained qualitative results on an application to swap the gender from male to female and vice-versa by successfully transferring style, pattern from one domain to another, and preserving key attributes such as face identity, hair color, and orientation. 
-Tuning hyperparameters of batch-size and slicing training data improved the computational time that was required to obtain translated images. -By considering feature mapping loss between the two domains, evaluated the domain translation accuracy. 
-Built an Image Generator on the trained network for real-time face-swapping. The Image Generator successfully showed style transfer in the form of hair color, facial attributes, expressions, and orientation.

This repository contains:
# DiscoGAN_model: 
Code for generating model and architecture of DiscoGAN (training + test on CelebA dataset)
# Results_DiscoGAN_model: 
Results obtained on 5 test images fter training on CelebA dataset for DiscoGAN_model code
![](ResultsfordiscoGAN.png)
# DiscoGAN_Image_Generator: 
Code for Testing our trained DiscoGAN model on real-world images
# Test_Images_DiscoGAN_Image_generator: 
Team members images given as input to the DiscoGAN_Image_Generator.ipynb code
# Plot_of_losses : 
Code for plotting generator loss, discriminator loss, feature mapping loss and reconstruction after training on DiscoGAN_model.ipynb code for CelebA dataset
