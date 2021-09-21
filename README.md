min_ssd1306i2c

Arduino Library for SSD1306 I2C OLED Module 64x128 pixel
Relased Sept 2021 by TeakSoon Ding ( Malaysia )
- Tested on Arduino Uno with the Arduino 1.8.15 IDE Sofware

The min_ssd1306i2c library is designed to be small as possible. Many minor error 
and boundry checks are not coded in order to keep the library small.
It has a built-in 7x5 pixel font array ( 95 chars, ranged from ASCII char 32 to 126 ). 

There are 5 files in the min_ssd130612c library package,

1. min_ssd1306i2c.h ( library source code - must install )
2. min_ssd1306i2c.cpp ( library source code - must install )
3. basic_demo.ino ( example program code - optional )
4. full_demo.ino ( example program code - optional )
5. full_demo_avr.ino ( example program code  - optional )

How to install min_ssd1306i2c library manually into Arduino IDE ?

1. Find out where is your "Arduino Working Folder"
From Arduino IDE Software Menu, File | Preferences...
Sketchbook Location:
[ "Arduino Working Folder" is listed here ]

2. Look for the folder name "libraries" inside the "Arduino Working Folder", Open the "libraries" folder

3. Create a new sub-folder name "min_ssd1306i2c" inside the "libraries" folder, Open the "min_ssd1306i2c" folder

4. Copy library source code "min_ssd1306i2c.h"   into the "min_ssd1306i2c" folder
5. Copy library source code "min_ssd1306i2c.cpp" into the "min_ssd1306i2c" folder

Optional:
6. Create a new sub-folder name "examples" inside the "min_ssd1306i2c" folder, Open the "examples" folder
7. Create 3 new sub-folders inside the "examples" folder, 
"basic_demo" folder
full_demo" folder
"full_demo_avr" folder

7. Copy example program, "basic_demo.ino"    into the "basic_demo" folder
8. Copy example program, "full_demo.ino"     into the "full_demo" folder
9. Copy example program, "full_demo_avr.ino" into the "full_demo_avr" folder

Close the Arduino IDE Software (if it is still opened) and Start the Arduino IDE Software. 
You can use the "min_ssd1306i2c" library now.

If you have done the optional steps to load the example programs, you can also open the example program
from your Arduino IDE Software Menu, File | Examples | min_ssd1306i2c | ... 


---

Folder Structure and files location,

"Arduino Working Folder" - libraries - min_ssd1306i2c - min_ssd1306i2c.h
                                                      - min_ssd1306i2c.cpp
                                                      - examples - basic_demo - basic_demo.ino
                                                                 - full_demo - full_demo.ino
                                                                 - full_demo_avr - full_demo.ino
                                                                 
---
-   https://github.com/teaksoon/teaksoon
<!---
Lets see how it goes here
--->
