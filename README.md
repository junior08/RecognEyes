# Face-Recognizer :sunglasses:
A Face Recogniser which works in real time!
You get 3 options:

## 1) Add a new face to the dataset of known people :heavy_exclamation_mark:.
  
 ### Important: Make a folder with the name 'people_folder' in the directory of this code and then proceed.
 Enter the name of the person and press ENTER when ready.
  
  
 A demo of this is shown below :wink::
  
  
  
 ![](https://github.com/junior08/Face-Recognizer/blob/master/add_face.gif) 



 
 ### Photos of the person are clicked and then saved in a folder with the person's name as the folder name.
  
  
  ![](https://github.com/junior08/Face-Recognizer/blob/master/added_faces.png)
  
  



## 2)  This option is for live recognition. :smiley:


   Our recognition system works!!
    
    
  ![](https://github.com/junior08/Face-Recognizer/blob/master/live.gif)\\
    
    


## 3) Finally on pressing 3, the exe file stops and you exit!  :v:

  
  


_______________________________________________________________________________________________________________________________________



## How does it work :question:

### 1) It takes in 20 images per face(person).
  
   i) Finds the face in the frame using a HAAR cascade.
  ii) Trims the unnecessary parts of the face
 iii) Does histogram equalization and resizes the images to 100 x 100
 
 These images are saved in a folder with the person's name.
 
 
 
 ### 2) For live recognitionn:
 
   i) Creates a LBHP face recogniser and trains it on the existing dataset.
   ii) Finds the face, does the same pre-processing as point 1.
  iii) Finds the face with the closest likeness to the current face within a certain threshold.
   iv) Displays the face along with the name of the person and a rectangle around their face.
