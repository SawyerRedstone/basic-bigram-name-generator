# Basic Bigram Name Generator
This project implements a character-level bigram neural network to generate names, inspired by Andrej Karpathy's [first video on Makemore](https://youtu.be/PaCmpygFfXo?si=e-UxbSgAoWTx4Wos), but built from memory and with my own deeper explorations.

My goal was to reinforce what I learned by re-creating the model without referencing the original code, and by teaching each concept in my own words and style. I've worked to format everything in a way that made the ideas less confusing for me, including:

- Custom examples not covered in the video.
- Deeper dives into certain topics that I initially found tricky.
- Step-by-step walkthroughs and visualizations of the model's behavior (like training on a single example and examining the gradients) to give a hands-on, intuitive feel.

All comments, markdown explanations, and formatting are entirely my own, written to make every step as clear as possible. No prior experience with neural networks or Makemore is required. This notebook is designed as a teaching tool for beginners.

I hope this project helps others start their own neural network journey, or makes these concepts a little less intimidating!

## Contents
This notebook walks through the full process of coding a basic, one-layer neural network, including:
- What a neuron really is. (Hint: it's just a bunch of numbers representing weights!)
- One-hot Encoding (its purpose and how it interacts with our network on a mathematical level).
- Turning model output into probabilities with the Softmax function + the math involved.
- Training the model with Negative Log Likelihood (NLL) loss and what that loss means.
- Understanding backpropagation at an intuitive level (via training the network on a single example and examining the gradients).
- Using the model to generate names by sampling letters one at a time.
