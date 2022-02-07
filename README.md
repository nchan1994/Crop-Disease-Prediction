# Crop-Disease-Prediction

# Background

In this project, I was contracted by Rooftop Republic (https://rooftoprepublic.com/) as part of a Hackathon 1.5 day event to build applications that would bring added business value to their business. With the implementation of technology and improving logistical operations as their focus, I decided to build a AI model that would help them predict and identify the level of heath of their crops, which will help increase their ability to grow crops that are healthy and sustainable.

A bit about the client:
Rooftop Republic builds and manages urban farms to transform under-utilised areas into vibrant natural spaces, create sources of nutritious organic food, and engage and empower communities to lead a sustainable lifestyle. They work closely with local farmers to build and sustain their urban farms.

# Objective

The objective of this Hackathon is to build an App that would add value to their business. As the supply of farmers is slowly decreasing in Hong Kong, there is a strong possibility that it would become difficult to hire farmers to manage Rooftop Republic's crops in the future. A big thing that Rooftop Republic rely on is the farmers expertise on evaluating the health and state of the crops. Therefore, I came up with the idea of building an AI App that can detect the health of the crops, which will lower Rooftop Republic's reliance on farmers in the futrue to evaluate the crop's health. 

# Solution & Approach

To build this AI app, I had to get data from online to build my CNN2D model with a multi-class classification output. By taking an image, the AI will process the features of the image and determine if the crop leaf is either 1) Healthy, 2) Diseased, 3) Has Rust, or 4) Has scabs. 

# Conclusion and Evaluation

The model built resulted in a 86% training accuracy, and 89% validation accuracy. While the model did pretty well in prediction and classification, I did note a few things that it could have been improved. 

What could have been done better:
- More images to train the model (i.e. More training data)
- More examples of different kinds of crops and plants leafs for better learning
- Testing with pre-trained models (e.g. Efficientnetb6)
- Hyperparameter tuning and Optimization

Future Considerations:
- Cross reference to farmers and their experiences and knowledge on plant health
- Collecting database on other crops and vegeatables 
- Expand AI classfication on other known problems (e.g. Macronutrient deficiencies) 
