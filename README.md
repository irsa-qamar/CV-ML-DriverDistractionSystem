# Distracted-Driver-Detection
There are in total 22424 Training Images. The image size is 640x480x3. There are in total 10 classes and approximately 2240 images in each class. There are 26 unique drivers performing 10 different actions.

For our initial analysis we selected a subset of the original data containing 11400 images across 5 categories. c0: safe driving c1: texting - right c2: talking on the phone - right c3: texting - left c4: talking on the phone - left

To bring down the processing time, we pre-processed the input images to scale down the resolution and colors Dimension from 640640 to 224224 Color from RGB to Gray Scale

To normalize the data, we divided each pixel with 255 so that we can have uniformly distributed values ranging from [0-1]
