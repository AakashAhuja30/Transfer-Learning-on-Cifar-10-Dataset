# Transfer-Learning-on-Cifar-10-Dataset


1. Built a baseline CNN with 2 convolution layers and 2 max pooling layers with RELU non linearity and He Initializer
2. Performed Data Augmentation on the Cifar-10 Dataset with 10 classes and train the same network using this augmented dataset.
  a)  Augmented dataset #1: Brighten every pixel in every image by 10%
  b)  Augmented dataset #2: Darken every pixel in every image by 10%
  c)  Augmented dataset #3: Flip all images horizontally (not upside down). As if they are mirrored.
  d) Augmented dataset #4: The original training set.
3. Performed Self Supervised Learning via Pretext- Set aside 50 examples per class(Total 500 examples). Initialize the weights of this small model using a pretext model's weights(More about Pretext model in colab notebook). This is what you call Transfer Learning. 
