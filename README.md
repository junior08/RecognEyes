# Face-Recognizer :sunglasses:
A Face Recogniser which works in real time!

## Instructions:
1) Make a folder with the name 'people_folder' in the directory of this code and then proceed.
2) Download the HAAR cascade and place it in the same directory. 
3) Run pip install opencv-contrib-python from cmd to install the additional features of OpenCV.<br /><br />


### You get 3 options:

## 1) Add a new face to the dataset of known people :heavy_exclamation_mark:.
  
 ### Important: Make a folder with the name 'people_folder' in the directory of this code and then proceed.
 Enter the name of the person and press ENTER when ready.
  
  
 A demo of this is shown below :wink::
  
  
  
 ![](https://github.com/junior08/Face-Recognizer/blob/master/add_face.gif) <br /><br />



 
 ### Photos of the person are clicked and then saved in a folder with the person's name as the folder name.
  
  
  ![](https://github.com/junior08/Face-Recognizer/blob/master/added_faces.png)
  
  



## 2)  This option is for live recognition. :smiley:


   Our recognition system works!!
    
    
  ![](https://github.com/junior08/Face-Recognizer/blob/master/live.gif)<br /><br />
    
    


## 3) Finally on pressing 3, the exe file stops and you exit!  :v:

  
  


_______________________________________________________________________________________________________________________________________



## How does it work :question:

### 1) It takes in 20 images per face(person). :camera:
  
   i) Finds the face in the frame using a HAAR cascade. <br />
  ii) Trims the unnecessary parts of the face. <br />
 iii) Does histogram equalization and resizes the images to 100 x 100. <br /><br />
 
 These images are saved in a folder with the person's name.
 
 
 
 ### 2) For live recognition: :+1:
 
   i) Creates a LBHP face recogniser and trains it on the existing dataset. <br />
   ii) Finds faces in live video stream, does the same pre-processing as point 1. <br />
  iii) Finds the face in our dataset with the closest likeness to the current face within a certain threshold. <br />
   iv) Displays the face along with the name of the person and draws a rectangle around their face.<br /><br /><br />
   
   
### About LBHP face recognizer :grin:: https://towardsdatascience.com/face-recognition-how-lbph-works-90ec258c3d6b
