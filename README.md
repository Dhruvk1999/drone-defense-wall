# drone-defense-wall

Steps to be followed

## Object Detection  
* This has to be done by OpenCV using just image processing
* If there is no reasonable accuracy we’ll explore deep learning techniques for the same purpose
    * This will make the whole the whole thing very complex
    * This will also involve detecting different objects in the image by OpenCV
    * Then the DL model will be used to select which of the objects in the image is a drone (or is it a bird or an UFO)
    
## Object Tracking 
Once the drone is detected it has to tracked for this specific purpose we’ll be using CAMShift algorithm.
