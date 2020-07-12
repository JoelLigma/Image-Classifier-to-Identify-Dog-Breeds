# Image-Classifier-to-Identify-Dog-Breeds
This is a project I completed for Udacity's AI Programming with Python Nanodegree Program.

The goal of this project was to develop an application that takes 3 lines of user input and then classifies dog images for the user using a pre-trained image classifier.
These inputs are:

- The images (any file path)
- The neural network architecture (ResNet, AlexNet, or VGG)
- The Image labels

**Principal Objectives**

- Correctly identify which pet images are of dogs (even if breed is misclassified) and which pet images aren't of dogs.
- Correctly classify the breed of dog, for the images that are of dogs.
- Determine which CNN model architecture (ResNet, AlexNet, or VGG), "best" achieve the objectives 1 and 2.
- Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result, given the amount of time each of the algorithms take to run.

In order to run the program, download all files and then run "python check_images.py" in the command line.

**Program Outline**

Time your program
- Use Time Module to compute program runtime

Get program Inputs from the user
- Use command line arguments to get user inputs

Create Pet Images Labels
- Use the pet images filenames to create labels
- Store the pet image labels in a data structure (e.g. dictionary)

Create Classifier Labels and Compare Labels
- Use the Classifier function to classify the images and create the classifier labels
- Compare Classifier Labels to Pet Image Labels
- Store Pet Labels, Classifier Labels, and their comparison in a complex data structure (e.g. dictionary of lists)

Classifying Labels as "Dogs" or "Not Dogs"
- Classify all Labels as "Dogs" or "Not Dogs" using dognames.txt file
- Store new classifications in the complex data structure (e.g. dictionary of lists)

Calculate the Results
- Use Labels and their classifications to determine how well the algorithm worked on classifying images

Print the Results
- You will need to repeat these tasks for each of the three image classification algorithms that are provided to you.


**Note**

Potential future change: Use os.path.splitext(). in order for my code to generalize image labels better. Plan is to remove .jpg endings.
