# Challenge_Resnet18_Fellowship.AI

# Challenge
Use a pretrained ResNet 18 and train on the Flowers dataset and then visualize the layer activations using GRADCAM for a mislabeled image of your weakest class. What additional steps would you take to improve the model without changing the number of epochs?

# Resources:
    A) ResNet 18
        main: https://pytorch.org/vision/stable/models.html#torchvision.models.resnet18
        tutorial: https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.htm
        
    B) Flowers
        main: 	http://www.robots.ox.ac.uk/~vgg/data/flowers/102/
        download: https://s3.amazonaws.com/fast-ai-imageclas/oxford-102-flowers.tgz
        sota: https://paperswithcode.com/sota/fine-grained-image-classification-on-oxford
        
 # What I did:
 Downloaded the dataset and made sure to locate images to folders based on their class and type. Meaning for folder train(training) you have a class 1 containing images so basically train/100/image.jpg
 
 
 # Results:
 I have tried to run the model using google colab with gpu but was not lucky enough and did it on my local computer and it was really slow and could not wait so long and just went basically at first with 3 epochs to see if things were working.
 Then did it with 1 epoch that's why the validation might look so bad. I guess I might need to do it with epoch of at least 150 to 300 epochs and playing with hyperparameters to see some improvement in the accuracy. I needed to hand the challenge today. Hopefully it is ok to have a fist glance at what I did in the first place.
