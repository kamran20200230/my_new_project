# my_new_project
building_AI
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Performing Object Detection with ImageAI

Now let's see how to actually use the ImageAI library. I'll explain step by step how you can build your first object detection model with ImageAI.
Final project for the Building AI course



## Background
|Our first task here is to create the necessary folders. For this tutorial we need the following folders:

Object detection: root folder
models: stores pre-trained model
input: stores image file on which we want to perform object detection
output: stores image file with detected objects




## Challenges

After instantiating the ObjectDetection class we can now call various functions from the class. The class contains the following functions to call pre-trained models: setModelTypeAsRetinaNet(), setModelTypeAsYOLOv3(), and setModelTypeAsTinyYOLOv3().

For the purpose of this tutorial, I'll be using the pre-trained TinyYOLOv3 model, and hence we will use the setModelTypeAsTinyYOLOv3() function to load our model.
## What next?

To detect objects in the image, we need to call the detectObjectsFromImage function using the detector object that we created in the previous section.

This function requires two arguments: input_image and output_image_path. input_image is the path where the image we are detecting is located, while the output_image_path parameter is the path to store the image with detected objects. This function returns a dictionary which contains the names and percentage probabilities of all the objects detected in the image.
![image](https://github.com/kamran20200230/my_new_project/assets/135314860/e4ae665d-2be4-4ac4-8d0d-7bb6c6b5c8da)
