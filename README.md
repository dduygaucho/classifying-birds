# classifying birds
 
 <h1> Dataset </h1>
 <p> Data set of 400 bird species.58388 training images, 2000 test images(5 images per species) and 2000 validation images </p>
 
 <p>The training set is not balanced, having a varying number of files per species. However each species has at least 120 training image files. This imbalanced did not effect my kernel classifier as it achieved over 98% accuracy on the test set.
 </p>
 <p>
One significant imbalance in the data set is the ratio of male species images to female species images. About 85% of the images are of the male and 15% of the female. Males typical are far more diversely colored while the females of a species are typically bland. Consequently male and female images may look entirely different .Almost all test and validation images are taken from the male of the species. Consequently the classifier may not perform as well on female specie images. </p>

<h1> Test results </h1>
<p> The model achieves up to 96% in the test set. For more information about data preprocessing, analysis and model training, please open the notebook </p>
