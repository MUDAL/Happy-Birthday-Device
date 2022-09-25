# Birthday_Gift_For_Sister  

A small device with the following hardware:  
1. Microcontroller  
2. I2C OLED  
3. Power supply unit  
4. Power switch  
5. Buzzer
6. LEDs
7. Batteries (7.4V)  

## What does it do  
It continuously plays a birthday song, displays some celebratory text on the OLED screen,   
and alternately toggles two LEDs.  
In order to do both tasks simultaneously, the **loop** function was dedicated to handling  
the display of information on the **OLED** while a **timer interrupt** was configured to handle  
the generation of music (the birthday song).  

## Credits  
1. Vector X (https://www.youtube.com/watch?v=d-WkHkuYSPQ)  
2. Adafruit OLED Library (The Adafruit_SH1106.cpp was modified to suit the Arduino   Nano) (Modification:: Wire.begin(sda,scl) to Wire.begin())     
3. http://cliparts.co/cliparts/pi7/Ky4/pi7Ky4xrT.png    
4. https://marlinfw.org/tools/u8glib/converter.html    

## Prototype  
![IMG-20220621-WA0000 (2)](https://user-images.githubusercontent.com/46250887/192158167-d4f36223-8d26-453b-8894-72b7033d33bf.jpg)


