# Patatap-Clone

This application allows you to press any key from A-Z - each keystroke generates a new circle shape and plays a unique sound based on the key pressed, based on https://patatap.com/.


Features: 
  
  PaperScript.js
    - used to create a circle shape at random coordinates on the screen on each unique key pressed
    - on every new frame, change circle color and scale it down 
  
  Howler.js 
    - play different sound bytes on key press
    - 'Howl' object with designated sound byte assigned to each key
    - keys A-Z grouped inside of JavaScript Object - each key assigned a color and Howl sound object 
