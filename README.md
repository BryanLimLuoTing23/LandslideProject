# LandslideProject

Currently experiementing with different models for one dataset.

About the SVM model:
- Every pixel in the image dataset is actually it's own data point. 
- From our understandings of landslides, we can already feature engineer the relevant feature points of the satellite imagery
- So instead of processing each image like in a CNN/UNET, I applied a SVM by treating each pixel as its separate data point. 
- Thus, UNET processes images with less computational power, and does not require manual feature engineering ( which we are able to do here due to our understanding of geology and landslides ). 
