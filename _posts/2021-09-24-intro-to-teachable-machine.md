---
layout: post
title: "An Introduction to Teachable Machine"
author: daniel
categories: [Tools]
tags: []
image: assets/images/24.jpeg
---

Teachable Machine is a free web-based tool to create machine learning (ML) models without any coding. No signup required.

Teachable Machine allows you to “train” an ML model to recognize certain patterns by supplying it with labeled data.

For example, you can create an ML model that when you give it a picture, it can tell you whether the picture contains a dog, a cat, or neither. To create this Cat-or-Dog model, there are three steps:
Gather many images of dogs, group them into one “Dog” category. Repeat for images of cats, grouping them into a “Cat” category. Repeat for pictures of other animals (or anything other than dogs and cats, really) that are neither dogs nor cats, grouping them into an “Other” category.
Provide your model with the labeled data; in this case, the classified images.
Train your model —Teachable Machine does this for you.

And, voilà, your model can now identify dogs and cats and differentiate them.

There are three different types of projects supported by Teachable Machine:
Image Project: “Teach a model to classify images using files or your webcam.”
Image project tutorial
Audio Project: “Teach a model to classify audio by recording short sound samples.”
Audio project tutorial
Pose Project: “Teach a model to classify body positions using files or striking poses in your webcam.” Pose project tutorial

Additionally, here is a playlist of tutorial videos detailing the process of using Teachable Machine.

Teachable Machine is built using a technique called transfer learning, which is turn based on neural networks. With that said, there are some important things to consider when using this tool:

ML models are inherently biased. Any bias in your training data will be reflected in the model’s decision-making process. Consequently, they can perpetuate negative human bias. This is a prevalent issue: large companies have been subject to controversy over their noticeably biased models. For example, Amazon had to scrap their internal recruiting AI system because it showed a bias against female candidates. Reportedly, the models were trained with resumes submitted to the company over a ten-year period, which mostly came from men.
Machine learning models based on neural networks resemble a black box in nature. While you might be able to tell that a dog is a dog based on their fur, snout, size, legs, etc, a neural network model can be mysterious in its decision-making process. It ultimately boils down to a bunch of weights and numbers that can seem arbitrary to humans. Thus, even though your model might be able to tell dogs and cats apart decently well, it’s very difficult to understand how it is doing that.
The quality of your model depends entirely on the quality of your data. If you give your model only pictures of dogs in grassy outdoor lawns, it might get confused when it tries to classify a dog inside a house with furniture and a tile floor. Similarly, if you give your model only pictures of a Siamese cat, it might not be able to recognize a Persian cat. To avoid this, your data should be as varied as possible, with the more (properly labelled) data the better.
