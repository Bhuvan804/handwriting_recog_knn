Handwriting Recognition using KNN </br>

I used KNN algo , k=5.</br>
The MNIST training data set is used in this notebook,taking 80% of data for train and rest 20% for test.</br>
Although, KNN doesn't use any training being Non-Parametric</br>
Here, we directly do computation during runtime.</br>
When pixel data is plotted for training, and Test image is given, its pixel value lies closest to (using Eucledian function) to its similar images.</br>
Thus a handwritten image of '7' would have similar pixel to (hence less Eucledian distance) others '7s' we plotted.</br>
