# Artificial Neural Networks applied in Football Analytics


During my project, I built different kinds of Artificial Neural Network (ANN) models in order to solve some problems and see new applications of data in sports analytics. To do so, I used TensorFlow, an open-source library for machine learning that is very optimised for this kind of models. I chose this library as it is one of the most popular ones.

As I started working with TensorFlow, I encountered a few backward-compatibility issues due to newer versions of the library not being able to run code written for older versions. Therefore, I made sure to use the same version of TensorFlow as the one used to prepare this project: 2.7 (latest stable version at the moment of writing this).

During the project, I built 3 different kinds of ANN, each to solve a different problem using a different dataset. I started by designing and training a Multilayer Perceptron (MLP) (or feedforward ANN) to compute a metric called Post-Shot Expected Goals (PSxG). Later on, I constructed a Convolutional Neural Network (CNN) to be used as an action selection model through spatial data. Finally, I designed an Autoencoder to reduce the dimensionality of a dataset consisting of aggregated player stats in order to apply clustering algorithms and find different groups of players.

It is worth noting that ANNs allow for lots of hyper-parameters to be tuned, as well as the many possible structures we can use. Finding the most appropriate design is sometimes regarded more as an art rather than a science, given that trying all possible combinations may be too power and time consuming. Due to the time limitation of my project, I only tried to find performance improvements by applying some tweaks on the model for the first exercise. For the rest, I focused on how can the different network structures be helpful given their nature. I didn't use methods such as cross-validation for model selection due to time limitations, but I am aware that these procedures should be used when dealing with real-world problems.

This project was provided to me as a graded exercise as part of the Sports Analytics Postgraduate I was part of this year (2022-2023). It was designed by FC Barcelona experts working in the Data Science team which are also teachers in this postgraduate that was created by FC Barcelona and UPC School.
