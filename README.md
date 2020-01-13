# Activity Detection Using Variational Autoencoders (VAE)

In this Project, We use the Variational Autoencoder in seperating football Images from ads. The VAE was trained using football images only, with this, when images from a different distribution is fed into the VAE the reconstruction loss is then considerably higher. Link to Meduim article: https://medium.com/analytics-vidhya/activity-detection-using-the-variational-autoencoder-d2b017da1a88


![](./images/other_images/front_page.jpg)


## Contents

### images 

The image folder contains four other sub-folders(epoch_images,Gifs, other_images,train_images.)

#### Train Images
Train Images contains a subset of the train images. Due to large volume, the whole folder could not be uploaded here. It is recomended in the event of use of this source code, more Images should be used in the training of this images.

#### Epoch_Images and Gifs

Epoch_Images contains the recontructed Images while training the Variational Auto-encoder, while the Gifs contains the Gifs made from this the Epoch_Images.

#### Other Images
This sub-folder conatins some Images used in the reconstruction test, to evaluate the accuracy of the built Variational Auto-encoder.

### data
The data folder contains data (csv files) containing the reconstruction losses of the various image classes considered in the evaluation of the Variational Auto encoder. 'loss_recon_more_aft.csv' contains the reconstruction loss of the american football class of images. 'loss_recon_more_ft.csv' contains the reconstruction loss of football images. 'loss_recon_more_nft.csv' contains the reconstruction loss of football images.

