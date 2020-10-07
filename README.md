# Age-Prediction-From-Facial-Images
**Objective:** to guess age of a person given his/her photo.

**Approach:** Principal Component Analysis (PCA) to perform dimensionality reduction of the given dataset. Then, train a linear regression model on the reduced-dimension dataset to learn their age.

**Data Files:**
1. [wiki_labled.zip](https://drive.google.com/file/d/1GBzJGe75ARybVTeVo5QLUnsJAeVu8331/view?usp=sharing): contains 60327 facial images kept in 100 folders, naming 00-99. Dimension of each image is 100 pixels by 100 pixels.
2. [wiki_labeled.mat](https://drive.google.com/file/d/1dVkUmGC2G_rZFb2tvy8vwV__ZKTUEzVJ/view?usp=sharing): contains meta information of each of the 60327 images.
3. [wiki_judge_images.zip](https://drive.google.com/file/d/1kfYQybBq52BK0joo5o_Ldlhw9SSRBh2c/view?usp=sharing): containing 2001 facial images of resolution 100x100.
4. [wiki_judgeX.mat](https://drive.google.com/file/d/1qvIozGjVDVuYK4prcvtgP-i04JJfVkFJ/view?usp=sharing): contains meta information of each of the 2001 images.
