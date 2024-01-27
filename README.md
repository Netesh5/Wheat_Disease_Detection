# Wheat_Disease_Detection
This model is train to classify the different disease occured in wheat plant. The model is built with CNN using Max pooling architecture with 2 dense layer containing 64 Neurone in each layer.

# About

* This model in Trained on over 5K images of wheat plant.
* The dataset is trained in 158 Batch Set, each containing 32 Images
* For resizing, images are converted into 256x256 dimension with 3 channel colors
* For max pooling 2D dimension kernel are used
* For convoultion layer 3D dimension layer is used

## For intergration in Mobile Devices
  
* To integrate the model in Mobile device TFLite is used
* TFLite model can be found in this repo : Flutter Application [https://github.com/Netesh5/gahu_rakshak]
* We can implement the model using offical Tensor flow package

## For preprocessing the image to upload in flutter application
* Before fitting the image directly into the model, it need to preproccessed
* We need to convert the image into 256x256 with 3 channel
* Then we need to convert the 3D images data to Tensor Array of Float32 or Unit8 type
* After the above step we can run data into binary form and fit in model
