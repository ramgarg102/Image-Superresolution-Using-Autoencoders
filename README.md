# Image-Superresolution
The aim of this project is to enhance the image quality of distorted or low quality images using Auto-encoders.

Here, the LFW dataset is used which contains around 13000 images of various people. The quality of the images is reduced to 1/4th of the original quality and the convoluted low quality images are fed into the encoder-decoder model. The expected output should be the original images. The model learns to create the actual image from low quality image thus acting as self supervised learning.
