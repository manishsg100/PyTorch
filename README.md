# PyTorch
Deep Learning with PyTorch on Python

In this session, we will see how to use PyTorch for building deep learning models. PyTorch was released in early 2017 and has been making a pretty big impact in the deep learning community. It's developed as an open source project by the Facebook AI Research team, but is being adopted by teams everywhere in industry and academia. As per my experience, it's the best framework for learning deep learning and just a delight to work with in general. By the end of this lesson, we'll have trained our own deep learning model that can classify images of cats and dogs. 

We will cover below points in mainly:

tensors - the main data structure of PyTorch. 

how to create tensors, how to do simple operations, and how tensors interact with NumPy.

autograd - that PyTorch uses to calculate gradients for training neural networks. Autograd is amazing. It does all the work of backpropagation for us by calculating the gradients at each operation in the network which we can then use to update the network weights.

Next we'll use PyTorch to build a network and run data forward through it. After that, we'll define a loss and an optimization method to train the neural network on a dataset of handwritten digits. 

we'll also learn how to test that our network is able to generalize through validation.

However, we'll find that our network doesn't work too well with more complex images. We'll learn how to use pre-trained networks to improve the performance of our classifier, a technique known as transfer learning.
