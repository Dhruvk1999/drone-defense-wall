# drone-defense-wall


## Object Detection  
* This has to be done by OpenCV using just image processing
* If there is no reasonable accuracy we’ll explore deep learning techniques for the same purpose
    * This will make the whole the whole thing very complex
    * This will also involve detecting different objects in the image by OpenCV
    * Then the DL model will be used to select which of the objects in the image is a drone (or is it a bird or an UFO)

<strong>Update: the whole thing is now using selective segmentation which is from a recent literature. </strong>

## Object Recognition
* RCNN is used for this purpose for now.
* data has to hand labeled
    
## Object Tracking 
* Once the drone is detected it has to tracked for this specific purpose we’ll be using CAMShift algorithm.

## Jammer:

-- Resonance ciuruit won't work so abandoning this
* Basic Jamming Circuit
* Switching circuit to switch to different LC pairs
* Different LC pairs would give  different frequencies to block
* for presentation atleast RF must be blocked
* Value of every L,C,R must be calculated. 
* Power supply connection and design
-- Abandoned
## Ardiuno 
* to-do
