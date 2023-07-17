# Project Outline:

1. Implemented a __Convolutional Autoencoder (CAE)__ to reconstruct images from the __Mnist dataset__.
![CAE_reconstruct_mnist](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/reconstructed_imgs.png)
2. Utilized the latent space of the __CAE__ to train an __SVM__ for image classification.
![svm](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/svm_confusion_matrix.png)
3. Proposed a denoising/deblurring, and inpainting __AE__ for denoising, deblurring, and inpainting specific images. <br>
Denoising:<br>
![denoise](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/denoising.png) <br>
Deblurring: <br>
![deblur](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/debluring.png)<br>
Inpainting: <br>
![inpaint](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/inpainting.png) <br>
4. Explored the application of __AE-based Recommender Systems__ using an 𝑀 × 𝑁 matrix. 
  . Excluded certain values from the matrix and trained the __AE__ to rectify them.
  . Compared __AE__ reconstruction with the original full matrix for validation.
  . In test scenarios, fed the __AE__ with user preferences to complete missing values and make recommendations on specific items.
  . Generated a randomly initialized initial matrix for __Recommender System__ testing.<br>
262/262 [==============================] - 1s 3ms/step - loss: 0.3619 - val_loss: 0.3551
Wall time: 36.8 s  <br>
5. Trained a __Variational AutoEncoder__ and investigated its ability to generate digits based on the __trained AE__.
![VAE](https://github.com/ilyesBoukraa/Variational-and-Covolutional_AutoEncoders/blob/master/output_imgs/variational_autoencoder.png)
