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

## Run
1. Create the copy of the project.
2. Open command prompt and change your current path to folder where you can find `app.py` file.
3. Create environment by command given below - $ `conda create -name <environment name>`
4. Activate environment by command as follows - $ `conda activate <environment name>`
5. Use command below to install required dependencies - $ `python -m pip install -r requirements.txt`
6. Run application by command - $ `python app.py` You will get url copy it and paste in browser.
7. You have sample_data folder where you can get images to test.

## Interface
![Screenshot from 2022-11-18 12-21-29](https://user-images.githubusercontent.com/50231750/202670325-035f9086-6bfa-451a-a544-7b5c179abbf9.png)

## Upload Images
![Screenshot from 2022-11-18 12-21-56](https://user-images.githubusercontent.com/50231750/202670404-9ccc7205-8887-4c73-b89b-b7feb9a0e610.png)

## Input
* Face 1:
![image](https://user-images.githubusercontent.com/50231750/202659679-a6933162-8c48-4a81-b05e-723d861b9e47.png)

* Face 2: 
![image](https://user-images.githubusercontent.com/50231750/202659731-00c1e8f7-e123-4e34-a9f0-cb91da559f77.png)

## Output
![image](https://user-images.githubusercontent.com/50231750/202659806-623b577f-2479-4623-a670-82eb600a842c.png)

## App Output
![Screenshot from 2022-11-18 12-22-09](https://user-images.githubusercontent.com/50231750/202670500-9a570a88-8eea-41bd-ac5c-1a7a6ba5941d.png)

## Conclusion
We started with downloading the pretrained model for face landmark and download the images from the internet on which we will work. Next we used CV2 and Dlib for preprocessing the images and used different functionalities to make reach to the end which is swapping the face of destination image with source image.
