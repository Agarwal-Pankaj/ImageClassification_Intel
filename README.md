# Practice Problem Intel Scene Classification Challenge in Analytics Vidhya


# Problem Statement:

How do we, humans, recognize a forest as a forest or a mountain as a mountain? We are very good at categorizing scenes based on the semantic representation and object affinity, but we know very little about the processing and encoding of natural scene categories in the human brain. In this practice problem, we are provided with a dataset of ~25k images from a wide range of natural scenes from all around the world. My task is to identify which natural scene can the image be categorized into.

# Dataset Description:

There are 17034 images in train and 7301 images in test data. The categories of natural scenes and their corresponding labels in the dataset are as follows - 
{ 
  'buildings' -> 0, 
  'forest' -> 1, 
  'glacier' -> 2, 
  'mountain' -> 3, 
  'sea' -> 4, 
  'street' -> 5 
}

Variable Definition image_name Name of the image in the dataset (ID column) label Category of natural scene (target column)

For Further Information follow the below Link:

Link: https://datahack.analyticsvidhya.com/contest/practice-problem-intel-scene-classification-challe/

# Transfer Learning using imagenet/inception_v3/classification

https://tfhub.dev/google/imagenet/inception_v3/classification/1

(Accuracy Level on LeaderBoard : 0.9269406393): 

# Scope for improvement

Data Augmentation

Resnet : https://tfhub.dev/google/imagenet/resnet_v2_50/classification/1
