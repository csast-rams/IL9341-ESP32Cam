# IL9341 Display for ESP32_CAM 
---
##### Fixed syntax errors found in the original IL9341 + ESP32_Cam example.

#### found at:  https://iamleon99.blogspot.com/2023/04/esp32-cam-ili9341.html
---
### Description
---

ESP32_CAM (AI_THINKER) and Adafruit IL9341 TFT display for displaying live video feed. 

Requires:

1) https://github.com/espressif/arduino-esp32.git

Libraries:

1) https://github.com/Bodmer/TJpg_Decoder.git
2) https://github.com/Bodmer/TFT_eSPI.git

---

#### Steps

1. Load CameraWebServer from examples --> arduino-esp32/esp32/camera.
2. Copy CamTolli9341.ino to sketchbook directory and delete CameraWebServer.ino, save sketchbook as CamTolli9341.
3. Navigate to TFT_eSPI libraries and replace the default User_Setup.h with the code in ***User_Setup.txt***.  
**(Instead of modifying the original file, rename it as _User_Setup.h and save the new as User_Setup.h)**

---

Notes:

- Flashlight (GPIO 4) is enabled by default on ESP32_Cam upon power-up.
- Disconnect 3.3v to TFT display while compiling and uploading if you are getting errors.
