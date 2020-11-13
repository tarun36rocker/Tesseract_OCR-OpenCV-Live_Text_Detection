# **Live Text Detector**
    by Tarun Krishnan
 Follow me on
   * Linkedin : https://www.linkedin.com/in/tarunkrishnan2000/
   * Github : https://github.com/tarun36rocker?tab=repositories
   -------------------------------------------------------------
 Now on to This Amazing and Simple Project that I made !
      
    The MAIN AIM was to be able to see if a computer could read text from a live video when
    a book or picture is shown to it just like a human !
    
    WHERE can we use this project ? This project can be used in every field possible to be honest ! It can be used 
    to ease the strain on humans to read from difficult images or videos and simply allow the computer to the 
    difficult task for us.
 So lets begin !   
    
 ![alt text](https://github.com/tarun36rocker/Open-contributions/blob/master/pic1.png)
 
 Just like how we need to brush every morning , we need to import few key modules that are required for the WHOLE
    program to run succesfully
    
   * cv2 :: This imports opencv which is used to interact with the live webcam feed
   * pytesseract :: Uses Tesseract OCR ( Optical character recognition ) which helps us in detecting the
                    text from the from the frames
                    
    Now we import our executable file so that we can import all features from Tesseract OCR
   ![alt text](https://github.com/tarun36rocker/Open-contributions/blob/master/pic2.png)
    
    
   * Line 4 is used to connect a capture instance to the default port which is connected to the webcam
   ![alt text](https://github.com/tarun36rocker/Open-contributions/blob/master/pic2.png)
   
    Now it's time to write our function that detects text from the live webcam feed! 
   ![alt text](https://github.com/tarun36rocker/Open-contributions/blob/master/pic2.png)
   * Line 9 is used to gets dimensions of the frame obtained through the webcam
   * Line 11 gets the boxes surrounding the words from the frame and some additional features
   * Line 14 is used as the first line of data contains titles of the feautres obtained which we don't need
   * Line 18 gets the various dimensions of the boxes surrounding the words detected
   * Line 20 draws a rectangle/boxes over the frame denoting the presence of the words
   * Line 22 adds the text of which word was read on the frame
   
   Now lets move on to the main 'while' loop that runs the whole function!
   ![alt text](https://github.com/tarun36rocker/Open-contributions/blob/master/pic2.png)
   * Line 27 gets the frames from webcam through the 'cap' ( capture ) instance that was defined earlier
   * Line 29 passes the frames to the text detection function
   * Line 31 finally outputs the frame after passing thorugh the function with the results
   * Line 32 waits for escape key to escape from floating window that was showing us the results
   * Finally Lines 37 and 38 releases the capture instance and closes the cv2 usage
   
  Lets now have a look at our results !
  ![alt text](https://github.com/tarun36rocker/Open-contributions/blob/master/pic2.png)
  
  Looks like computers are able to read text like humans after all ! 
  
    This is Tarun Krishnan signing off , hope you learnt something from my project !
 
