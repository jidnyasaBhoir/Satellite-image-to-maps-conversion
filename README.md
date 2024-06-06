The Satellite Image to Map Translation project aims to develop a deep learning model using Conditional Generative Adversarial Networks (CGAN) Pix2Pix to translate satellite images into corresponding map representations.
The primary objectives of the project are as follows to train a CGAN Pix2Pix model capable of generating high-resolution map images from low-resolution satellite images.
and evaluate the quality of the generated maps based on quantitative metrics.
The dataset used for training and testing the CGAN Pix2Pix model consists of pairs of satellite images and corresponding map images.
ay include images of various geographical regions, terrains, and land use types.

The project methodology involves the following steps:
Data Preprocessing: Satellite images and map images are preprocessed, resized, and normalized to facilitate model training.
Model Architecture: A CGAN Pix2Pix architecture, comprising a generator network and a discriminator network, is designed and implemented using TensorFlow or PyTorch. The generator network learns to generate realistic map images from satellite images, while the discriminator network distinguishes between real and generated map images.
Model Training: The CGAN Pix2Pix model is trained on the preprocessed dataset using an adversarial training strategy. The generator aims to minimize the difference between generated and real map images, while the discriminator aims to distinguish between them.
Model Evaluation: The trained model is evaluated on a test dataset to assess the quality of the generated map images. Quantitative metrics use to measure accuracy of the generated maps.
