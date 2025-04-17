# What Does a Model Output and How To Interpret It
## What is training and validation loss?
Training loss is the error rate on the training data. This is an indication of how well the model works in training. Ideally this value should reduce as the model progresses and learns. 
Validation loss is the error rate in the validation data set. This is also a good indication of how well the model is working.
## What is a confusion matrix
A confusion matrix displays all of the image classes across each axis with one refrencing what the model thought it was and the other what the image actually was. The matrix will show the reader what images the model correctly found and which ones it got wrong and what it believed they were. 
## What is a t-SNE graph
A t-SNE graph takes a very high dimensional vector associated with every image and compresses it into two dimensions. It then displays each image (coloured by its class) and plots them on a graph. A good model will have images from each class grouped together and away from other classes. 

## Some key terms
**epoch** - This represents one full pass through a data set. 

**batch size** - This is the amount of images processed before updating model weights

**error rate** - This is the rate at which the model incorrectly determines the image

