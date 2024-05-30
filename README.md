# In this project we will go through whole model building for a oceanic data to predict the hieght of the wave 

-> we will dive into filling nan values for various type of data by analyzing the distribuion
-> Then removing the outliers using iqr method, where the data which below the 25% and above the 75% of the data are removed using iqr method
-> Attribute selection based on univariate selection.
   -^ we will aslo see which attribute selection method we need to use based on the structure of data we have
-> Rescaling the data based on the skewness
   -^ both minmaxscaler and standard scaler is used
-> Using kfoldcrossvalidation which is gold technique to evaluate the model 
-> I used to knn regressor as it finds a good prediction for non-linear data

(Note* : You can also experiment with multiple techniques and methods to find out the best method for your data, no method is universal for any thing)
=> After going through this repo, you will get the basic strong understanding of how to preprocess and build a model based on your data by visulizing it with various
   tools

libraries used:
scikit learn,pandas,matplotlib,numpy,seaborn


=> Happy learning :)  