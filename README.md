# face-swapping-application
In this project, I extracted faces of human beings from a given image. I used a pre-trained model to extract landmarks from the faces.

I took a source image and a destination image and replace the face of destination image wiht source image.

## Scope
We used DLIB for this project and it's a landmark's facial dete4ctor with pre-trained models, dlib is used to estimate the location of coordinates(x,y) that map the facial points on a person's face. 

This product can be used for learning and understanding different concepts of computer vision. It can be used to build augmented reality applications like Snapchat, etc. 

## Steps
1. Downloading the pre-trained model for shape predictor. 
2. Creating a function for extracting the index. 
3. Load the source and destination image from the internet. 
4. Converting the images into numpy array.
5. Converting images into greyscale for better results. 
6. Load face detector and face landmarks predictor using `dlib`.
7. Perform triangulation on the images to cut out the face. 
8. Creating empty masks for images. 
9. Swapping the image for the face on the destination image. 
10. Using seamless cone for adjusting colour scheme. 

## Technology
1. Python
2. OpenCV
3. Dlib
4. Flask


