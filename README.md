# WoC6.0-DL-neural-style-transfer-muskankhare
In the Winter of Code 6.0 challenge, this repository hosts a project on Neural Style Transfer, an intriguing synergy of deep learning and art. Leveraging Convolutional Neural Networks such as VGG19, it seamlessly merges the content of one image with the stylistic elements of another, resulting in distinctive and visually appealing compositions.

# Overview:

Neural style transfer is a fascinating project that merges deep learning with art, harnessing the power of Convolutional Neural Networks (CNNs) to blend the content of one image with the stylistic elements of another. This technique involves two primary components: a content image (like a photograph) and a style image (typically an artwork). By employing a pre-trained CNN, such as VGG19, the model extracts feature representations of both content and style. The goal is to minimize the content and style losses, where the content loss ensures the output image retains the original content's structure, and the style loss infuses the artistic elements from the style image. This optimization process iteratively updates the output image, effectively 'transferring' the artistic style onto the content image, resulting in a unique, aesthetically blended creation. 

# Why (this project /this technology)?:

Advanced Deep Learning Techniques: Explore cutting-edge techniques in deep learning, such advanced CNN architectures.
Creative Applications of AI: Understand the interplay between artificial intelligence and creative processes.
Complex Optimization Problems: Learn to handle complex loss functions and optimization strategies unique to style transfer.
Interaction with Research Papers: Hands on experience reading research papers and implementing them from scratch.

# Concepts Covered:

Advanced CNN architectures
Loss Functions in Style Transfer
Optimization Techniques in Deep Learning


# Overall Development Pipeline:

Preprocessing:  Gather and process images for content and style.

Model Building: Design and implement CNNs for style transfer.

Training the Models:  Train the model with a focus on minimizing style and content loss.

Evaluation: Evaluate the aesthetic and technical aspects of the generated images.


# Tools and Technologies:

Python Programming Language

PyTorch for building neural networks

Jupyter Notebook or similar IDE for development (Google Colab is one such option)

# Learning Resources: 

Python: Python Official Documentation

PyTorch: PyTorch Official Tutorials

Computer Vision Basics: Computer Vision in Python by DataCamp


# Phase-wise division of the project

## Phase 1 :

Set up the development environment (Python, PyTorch, IDE) or the user can directly use google colab

Learn basic concepts of Python and PyTorch.

Collect some images and artwork from the internet (you can use web scraping for this)

Read about simple CNNs, and try out implementing an image classifier (preferably VGG 19).

## Phase 2 :

Read the Neural style transfer research paper, and try to implement the paper from scratch.

Try out neural style transfer with Resnet models, and see if something interesting pops up.

Document the results.

Create a streamlit page allowing users to upload an image, and then select a style from a dropdown menu, and get the final style transferred image after the processing.

# Additional features (OPTIONAL):

Experiment with different neural network architectures for feature extraction.

Visualize the training process using TensorBoard.







Project Setup Guidelines and Installation Instructions:
It is advised to use a cloud environment like Google Colab or Kaggle to avoid setting up the environment. For a local setup:
Python Installation: Python Official Site
PyTorch Installation: Follow the instructions on the PyTorch website
IDE Setup: Recommendations include Jupyter Notebook,or Visual Studio Code.

Mentors:
Mihir Agarwal - agarwalmihir@iitgn.ac.in
Hrriday Ruparel - hrriday.ruparel@iitgn.ac.in
Kishan Ved - kishan.ved@iitgn.ac.in
Shreyans Jain - shreyans.jain@iitgn.ac.in
Srikar Padaliya - +91 6358820530, 202101095@daiict.ac.in
Takshay Makadia - +91 9265589213 202101414@daiict.ac.in

