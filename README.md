# Task 2 Unsupervised classification of images



Dataset - https://drive.google.com/file/d/1wSW18_sQzlQ7xN3Y41UhfOlmCL8dhu-J/view?usp=sharing


Here is a dataset for unsupervised image classification. 57898 images are classified into 5 persons (clusters), I have ignored images of people wearing masks and also images with no people in them.

</br>
<p> Here are some of the sample images from the training set </p>
</br>
<p align='center'>
  <img src="./images/Screenshot 2022-11-06 111219.jpg">
 </p>

</br>


</br>
<p>Here are some of the images of people wearing masks</p>
</br>
<p align='center'>
  <img src="./images/Screenshot 2022-11-06 114751.jpg">
 </p>
<p>This is a clustering task, I have used InceptionV3 model and transfer learning to extract features on the data set and applied k-means clustering on these images. I have chosen k=5 as a starting point</p>


