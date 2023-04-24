# IL9341 Display for ESP32_CAM 
---
### original code:  https://iamleon99.blogspot.com/2023/04/esp32-cam-ili9341.html
---

<br>

### Description
---

ESP32_CAM (AI_THINKER) and Adafruit IL9341 TFT display for displaying live video feed. 

Requires:

1) https://github.com/espressif/arduino-esp32.git

Libraries:

1) https://github.com/Bodmer/TJpg_Decoder.git
2) https://github.com/Bodmer/TFT_eSPI.git

---

#### steps for replicating repository

1. Load CameraWebServer from examples --> arduino-esp32/esp32/camera
2. Copy CamTolli9341.ino to sketchbook directory and delete CameraWebServer.ino, save sketchbook as CamTolli9341
3. Navigate to TFT_eSPI libraries and replace the default User_Setup.h with the IL9341-ESP32Cam/User_Setup.h configuration

