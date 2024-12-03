# waveshare ESP32 S3 N8R8 LCD 7
Waveshare ESP32 S3 N8R8 LCD 7''

This is not for everyone, it's optimized for personal use, but a source I share to refer to.

And if it is necessary to adjust the backlight brightness, it can be adjusted by connecting the pin below and the remaining GPIO pin(ex:GPIO6) of ESP32 module.

![image](https://github.com/user-attachments/assets/feae9bb1-c0bd-4d50-bc0a-b0f707b64af7)

Please refer to the link below except base and hw setting.

https://github.com/plplaaa2/esphome-lvgl-480

This is a sample video.

https://www.youtube.com/shorts/WfNRwrhKC6Q?feature=share

The code used for the device in this video is personalized and cannot be used by other users. The cool weather page and other menus are components that are only available in Korea and my Homea Assistant. If you want to use this, you need to be able to understand and modify ESPhome LVGL. If you can't, no matter how much you receive the yaml file, you can't use it.

If that is possible, you can modify the yaml file I released below to suit your country and your home assistant.

HW code

https://github.com/plplaaa2/waveshare-7

LVGL code

https://github.com/plplaaa2/esphome-lvgl-480

The yaml file in this link is a yaml file modified to use the yaml file of the device shown in the original video of the shorts above for other devices (guition esp32 s3 480 4' display switch). Therefore, it can also be used for waveshare esp32 s3 LCD 7'. (as long as you modify some resolution)

The reason I can't make this an open source is because my code is already over the 10000 line. I'm not a programmer, so I'm not confident of organizing this to the level of disclosure.
