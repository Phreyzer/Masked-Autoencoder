# Masked Autoencoders

This [notebook](https://github.com/Phreyzer/Masked-Autoencoder/blob/main/Masked_Autoendoder.ipynb) shows a usage of Masked Autoencoders (MAE) applied to the MNIST database.

As explained in the paper "Masked Autoencoders Are Scalable Vision Learners" [1] an MAE receives an image, divides it into patches and some of them are masked. The model uses attention mechanism to retain positional information about the patches and, based on the visible patches, try to reconstruct the unseen ones.

The code below is inspired by the one found on the Keras website in the topic "[Code examples / Computer Vision / Masked image modeling with Autoencoders](https://keras.io/examples/vision/masked_image_modeling/)" [2]

[1] He, Kaiming, et al. "Masked autoencoders are scalable vision learners." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2022.

[2] https://keras.io/examples/vision/masked_image_modeling/

---

Bagni Junior, W. (2024). *Masked-Autoencoder* (v1.0). GitHub. https://github.com/Phreyzer/Masked-Autoencoder/
