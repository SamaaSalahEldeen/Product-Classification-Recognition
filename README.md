1.
Apply Image preprocessing or Feature Extraction techniques .
2.
Train classification model to determine the product category using Classical computer vision or deep learning.
3.
Train a shot learning model (e.g., Siamese) to verify if a product exists and recognize its type.
Part A) Product Classification Data
The Dataset for the classification part has 20 different products where each product has training folder and validation folder, the number of training images for each product ranges from (6-11 images), while the number of validation images for each product ranges from (1-3 images).
➔
In Part 1 classification,
  I train the model using all the training images belonging to the 20 different product classes.I also report the validation accuracy on all the validation images. So, i concatenate the validation sets from the 20 folders in this part.
  
Part B) Product Verification
    The Dataset for the Verification/Recognition part has 60 different products, where each product has number of images ranging from (6-14). Since here the task is shot learning thus the validation folders are totally different from the training folders where the first 40 product are considered the training data, and the remaining 20 products are considered the validation data.
➔
In Part 2, I train the model using all the training images belonging to the 40 different product classes for  shot learning task. and I validate the model performance on the 20 unseen products in the validation folders. I also report the validation accuracy.
