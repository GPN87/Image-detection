# Image-detection
##Work in progress
Currently a tensorflow-built convolutional neural network model that can detect whether an image is an Eastern Rosella, or a Crimson Rosella (for some reason..)
The next step will be building the capability for the model to identify if something is niether a crimson rosella or eatern rosella. I need to mess around with the prediction thresholds to do this.
Ultimately I'd like the serve it on a flask application, and build in a user-submission function. If the bird submitted can't be detected, it would create a new class for that bird, labelled by the user.

##Access
The notebook has been developed using google colab, and the training images were accessed by mounting the notebook to Google Drive.
