# Cat or Dog Classifier: AI-Powered Pet Identification

Final project for the Building AI course

## Summary

This project uses a neural network to classify whether an animal is a cat or a dog based on physical features like height, weight, and body length. It’s a lightweight, interpretable model built for quick deployment and educational purposes.


## Background

This project addresses the challenge of quick and automated animal identification, particularly in pet shelters or vet clinics. With limited resources and time, staff often need a fast way to catalog animals. AI can help streamline this process.

* Misclassification of animals in shelters

* Time-consuming manual input and decision-making

* Lack of accessible tech for smaller clinics or rural shelters

My motivation is to demonstrate how even simple models can solve real-world classification problems effectively, and to practice using neural networks in applied settings.


## How is it used?

The model takes three numeric inputs: height, weight, and length of the animal. These are fed into a trained neural network which outputs a probability between 0 and 1. If the value is above 0.5, it's classified as a dog; otherwise, as a cat.

This solution is ideal for:

* Animal shelters and clinics

* Mobile animal rescue units

* Educational tools for learning about neural networks

Users can input values through a simple web or command-line interface. Care should be taken to calibrate measurements properly to ensure accurate predictions.

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">
```


## Data sources and AI methods
The dataset used is a synthetic collection representing physical measurements of cats and dogs, or optionally a public dataset such as the Kaggle Dogs vs Cats dataset.

Data Attribute	Description
Height	In centimeters
Weight	In kilograms
Length	From nose to tail tip

AI Methods:

* Feedforward neural network

* Sigmoid activation for output

* Identity or ReLU in hidden layers

* Trained using supervised learning and binary cross-entropy loss

## Challenges

This model does not handle:

* Mixed-breed animals or unusual measurements

* Image-based identification (this model is numeric only)

* Real-world noise or outliers in input

Ethical considerations:

* Ensure predictions aren't used for medical decisions

* Avoid bias by ensuring the dataset is representative

## What next?

The next steps could include:

* Expanding the model to accept image inputs via CNNs

* Adding more animal classes (e.g. rabbit, fox)

* Integrating into a mobile app with camera + manual input options

Support needed:

* More varied training data

* UI/UX design help for end-user tools

* Guidance on deploying lightweight AI to edge devices


## Acknowledgments

* Based on concepts learned from the Building AI course by University of Helsinki

* Image: Sleeping Cat on Her Back by Umberto Salvagnin / CC BY 2.0

* Thanks to open datasets and educational materials that made this project possible
