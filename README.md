# Age-Prediction-From-Facial-Images
**Objective:** To guess age of a person given one's photo.

**Approach:** Principal Component Analysis (PCA) to perform dimensionality reduction of the given dataset. Then, train a linear regression model on the reduced-dimension dataset to learn their age.

**Training Data:**
1. [wiki_labled.zip](https://drive.google.com/file/d/1GBzJGe75ARybVTeVo5QLUnsJAeVu8331/view?usp=sharing): contains 60327 facial images kept in 100 folders, naming 00-99. Dimension of each image is 100 pixels by 100 pixels.
2. [wiki_labeled.mat](https://drive.google.com/file/d/1dVkUmGC2G_rZFb2tvy8vwV__ZKTUEzVJ/view?usp=sharing): contains meta information of each of the 60327 images.

**Testing Data**
1. [wiki_judge_images.zip](https://drive.google.com/file/d/1kfYQybBq52BK0joo5o_Ldlhw9SSRBh2c/view?usp=sharing): containing 2001 facial images of resolution 100x100.
2. [wiki_judgeX.mat](https://drive.google.com/file/d/1qvIozGjVDVuYK4prcvtgP-i04JJfVkFJ/view?usp=sharing): contains meta information of each of the 2001 images.

![alt text](https://drive.google.com/uc?export=view&id=1P6wu2p1q7p10lOv19MyJf8sT9hpudi1z)
