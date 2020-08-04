# Learn ML Basics

[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning) is a rapidly evolving field which focuses on computer algorithms that improve over experience. The experience can take the forms of training data, trial and error in a simulated environment, and a lot more.

My goal with this repository is to create an easy to follow and well paced program that relies entirely on online resources. I am not seeking to create a classification of all available resources on the topic, as there are many of those, and in order for them to be of any use one must already know the basics of the field.

As of now, this repository contains resources centered mostly around deep learning. I hope to add more as I learn and discover the field. I an in no way qualified for this as I am just a begginer, so this is more of a documentation of my learning proccess.

I hope that the material found here can bring anyone with basic programming knowlage to an intuitive understanding of the main concepts behind deep learning, and the ability to create basic DL classifiers, as well as enough understanding to learn more independently.

## Contents

- [Step by Step Program](#step-by-step-program)

- [Software and IDEs](#software-and-ides)

- [Prereqisites](#prerequisites)

- [Theory](#theory)

- [MOOCs](#moocs)

- [Basic DL in TensorFlow](#basic-dl-in-tensorflow)

- [Non Programming Lectures](#non-programming-lectures)

## Step by Step Program

This section contains a recommended order in which the material in this repository should be learned. This should only act as a general outline, so I encourage anyone to try more resources about various other topics in the field of ML.

- Install the [listed software](#software-and-ides). You can start by installing only Python and VSCode, and add Anaconda and CUDA later.

- Make sure you know the [prereqisites](#prerequisites). Watch the math videos in order, and learn python before or after that.

- If you wish to have a bit more background in CS, enroll to [CS50AI](https://www.edx.org/course/cs50s-introduction-to-artificial-intelligence-with-python). This step is completely optional.

- Watch the first Playlist listed in the [theory](#theory) section (you can also read the book if you want).

- Go through the entire [Basic DL in TensorFlow](#basic-dl-in-tensorflow) part. As you watch it, use the remaining resources in the [theory](#theory) section.

## Software and IDEs

- [Python](https://www.python.org/downloads/) is currently the best language for those who are new to machine learning, as it enables to do a lot very simply. I recommend installing python 3.7 as it has the best library support at the date of writing this.

- [VSCode](https://code.visualstudio.com/) is an open source IDE that can be used with python using the python extension that can be installed from within the software. I find this IDE really simple and useful as it supports both regular python script as well as ipynb notebooks.

- [Anaconda](https://www.anaconda.com/products/individual) is an open source distribution of python that contains many of the basic ML libraries as well as many other useful ones. It is not necessary at all on a begginer level, but it has a few advantages such as great package management as well as built in jupiter support.

- [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit) is an API for using NVIDIA GPUs. Download version 10.1 if you want to use it with TensorFlow. Alternatively you can run "conda install -c anaconda cudatoolkit" in the Anaconda prompt (it worked for me with TF 1.5). Then run "conda install tensorflow-gpu" to get tensorflow. To check if TensorFlow sees your GPU open python and print(tf.test.is_gpu_available).

## Prerequisites

To deeply understand the basic theory it is highly recommended (yet not necessary) to understand multivariable calculus and linear algebra matrix operations. You also need to know basic python and programming.

- [Essence of Linear Algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)

- [Essence of Calculus](https://www.youtube.com/watch?v=WUvTyaaNkzM&list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)

- [Multivariable Calculus](https://www.youtube.com/watch?v=TrcCbdWwCBc&list=PLSQl0a2vh4HC5feHa6Rc5c0wbRTx56nF7) (if you want you can stop at either 25 or 34)

- [Introduction to Python 3 Programming Tutorial](https://www.youtube.com/watch?v=eXBD2bB9-RA&list=PLQVvvaa0QuDeAams7fkdcwOGBpGdHpXln) (if you are not familiar with python)

## Theory

As ML and DL are very differnt paradigms than regular programming approaches, thare are many key concepts that need to be well understood in order to progress effectivly.

- [Neural Networks](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) is a youtube series by 3Blue1Brown covering the basics of deep neural networks in detail. I highly recommend watching it and writing main ideas and equations as you do so.

- [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) is a free online book that covers many of the same topics as the 3Blue1Brown series and more, with slight differences in notation and presentation. There is no need to read everything in order to get started with the programming, but if you do, the learning will be easier.

I recommend watching these after you tried creating basic linear deep neural networks:

- [Convolutional Networks | Stanford](https://www.youtube.com/watch?v=bNb2fEVKeEo)

- [Recurrent Networks | MIT](https://www.youtube.com/watch?v=SEnXr6v2ifU)

- [Understanding LSTM Networks](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)

## MOOCs

- [CS50AI](https://www.edx.org/course/cs50s-introduction-to-artificial-intelligence-with-python) is a massively open online course held by Harvard. It covers general practical and theoretical ideas in AI, and has quizes to test yourself as well as graded assignments in python. I highly recommend it, it is self-paced and completely free (unless you want the edX certificate, which isn't neccessary at all in my opinion). So create an edX account and enroll if it sounds interesting.

## Basic DL in TensorFlow

There are two great DL libraries in python - TensorFlow and PyTorch. From my expirience, TensorFlow is much easier to work with especially in terms of data preperation. It is very high-level, so I encourage you to make sure you understand the basics by creating deep neural nets from scratch.

- [TensorFlow Playground](https://playground.tensorflow.org/) is an interactive tool for getting the intuition behind key ideas in DL, such as activation types, dataset features, and overfitting.

- [Neural Networks from Scratch](https://www.youtube.com/watch?v=Wo5dMEP_BbI&list=PLQVvvaa0QuDcjD5BAw2DxE6OF2tius3V3) is a series that will guide you to create deep learning algorithms in raw python and numpy. At the time of writing this the series is not complete but this can be seen as a great opportunity - try and [complete it yourself](#theory).

- [Deep Learning basics with Python, TensorFlow and Keras](https://www.youtube.com/playlist?list=PLQVvvaa0QuDfhTox0AjmQ6tvTgMBZBEXN)

## Non Programming Lectures

- [MIT Deep Learning Basics: Introduction and Overview](https://www.youtube.com/watch?v=O5xeyoRL95U)

- [Deep Learning State of the Art (2020) | MIT Deep Learning Series](https://www.youtube.com/watch?v=0VH1Lim8gL8)

- [AI Podcast by Lex Fridman](https://www.youtube.com/user/lexfridman) (it isn't really related to learning, but it is a great inspiration)
