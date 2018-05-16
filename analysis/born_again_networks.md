# Title: Born Again Neural Networks

## Quick Summary:
This is a method that allows for improvement on a network with a particular data set by using KD (knowledge distillation). What happens here is a model is trained on data (the teacher) a new model is trained with the weights of the teacher (a student) with a tweaked loss function that then does better than the teacher. "The idea is typically to transfer the knowledge of a high-
capacity teacher with formidable performance to a more
compact student"

## What I found interesting
The analogy of the student becoming the master. This seems comparatively superior to using an ensemble of neural networks

## What was confusing
It was a little hard to first understand the "Dark Knowledge" since that concept was new to me.

## Further topics to research based off this paper:
Dark Knowledge from Geoffrey Hinton

## Possible Applications of Paper's Idea:
Using Born Again Networks instead of ensembling a ton of neural networks
