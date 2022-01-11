Handwriting Recognition using KNN

I used KNN algo , k=5.
The MNIST training data set is used in this notebook,taking 80% of data for train and rest 20% for test.
Although, KNN doesn't use any training being Non-Parametric
Here, we directly do computation during runtime.
When pixel data is plotted for training, and Test image is given, its pixel value lies closest to (using Eucledian function) to its similar images.
Thus a handwritten image of '7' would have similar pixel to (hence less Eucledian distance) others '7s' we plotted.
