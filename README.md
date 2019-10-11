## What it does:
#### It takes a webcam stream and predicts the hand symbol being shown
## How to use:
#### Run the FinalTester.ipynb file to see the result prediction.
## Dataset:
#### The dataset was manually generated by taking 500 + 500 pictures of my hand through the webcam and filtering the skin range out, applying blur to smoothen the edges and thresholding the image to black or white
## Model: 
#### Tried various models with tensorflow callbacks ( can be checked in logdir ) and set the model to 3 layered 128 node CNN with binary cross entropy classification.
