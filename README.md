# Project Outline:

1. Implemented a __Convolutional Autoencoder (CAE)__ to reconstruct images from the __Mnist dataset__.
![CAE_reconstruct_mnist](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/reconstructed_imgs.png)
3. Utilized the latent space of the __CAE__ to train an __SVM__ for image classification.
4. Proposed a denoising/deblurring, and inpainting __AE__ for denoising, deblurring, and inpainting specific images.
Denoising:
![denoise](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/denoising.png)
Deblurring:
![deblur](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/debluring.png)
Inpainting:
![inpaint](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/inpainting.png)
5. Explored the application of __AE-based Recommender Systems__ using an 𝑀 × 𝑁 matrix. 
  . Excluded certain values from the matrix and trained the __AE__ to rectify them.
  . Compared __AE__ reconstruction with the original full matrix for validation.
  . In test scenarios, fed the __AE__ with user preferences to complete missing values and make recommendations on specific items.
  . Generated a randomly initialized initial matrix for __Recommender System__ testing. 
6. Trained a __Variational AutoEncoder__ and investigated its ability to generate digits based on the __trained AE__.
![VAE](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/variational_autoencoder.png)
