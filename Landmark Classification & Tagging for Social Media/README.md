# Landmark Classification & Tagging for Social Media

## In this project, we had three distinct parts: 

1) CNN classifier from scratch for landmarks
2) CNN classifier built using transfer learning for landmarks
3) An algorithm to use the second CNN to classify landmarks

The minimum required test accuracy for the first part was 20% and 60% for the second part.

For the CNN built from scratch, I was able to get a test accuracy of %31. For the CNN built utilizing a vgg16 pre-trained model, I got %74 test accuracy. 

The details of the design, architecture, training, and testing are all included in the project's Jupyter notebook. The workspace-utils.py is a script to keep the workspace from automatically disconnecting during training
