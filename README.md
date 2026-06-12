# Handwritten Digit Classifier

I had the theory of neural networks in my head for a while — 
this project was just me trying to see how it actually works.

In a world where everyone's building these with PyTorch and TensorFlow, 
I was here trying to do it with just Python and NumPy — sounds crazy, I know.

But while learning deep learning, I came across this idea: neurons that fire 
together, wire together. So I figured, why not make my own neurons fire harder 
by building this from scratch before jumping to frameworks. Kind of funny but 
that was the whole point — let the concepts sink in, build stronger connections, 
then see if it actually works.

And well, it did. 

## Dataset
MNIST — 42,000 handwritten digit images from Kaggle Digit Recognizer competition.

## What I built
A CNN that looks at a 28x28 image and predicts which digit it is.
Went with CNN over a plain neural network because it understands
spatial patterns in images — edges, curves — rather than just raw pixels.
Got 98.8% validation accuracy.

## Stack
Python, NumPy, Pandas, Matplotlib

## What actually made sense after doing this
- Normalization — why you can't just feed raw 0-255 values into a network
- Reshape — what it means for an image to be "flat" vs a 2D grid
- Overfitting — read about it a hundred times, understood it when Dropout actually improved my results
- The whole pipeline — loading data, preprocessing, training, evaluating, generating predictions
- Difference between training accuracy and validation accuracy and why that gap matters

## Author 
Sarishty Dogra
