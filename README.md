#oCam - 5MP USB 3.0 Color Board Camera
###Model No. oCam-5CR-U3 - [sales website](http://www.hardkernel.com/main/products/prdt_info.php?g_code=G145231889365)

![ScreenShot](images/oCam_model.jpg)

* **Easy**: oCam does note require any device driver to be installed on the host PC or the Odroid-XU4
* **Versatile**: oCam supports the M12 lens format of various focal lengths for different needs
* **Low CPU usage**: oCam supports USB 3.0 with direct memory access, allowing data to be written to main memory without going through the CPU
* **Good for embedded system**: oCam is verified with the Odroid-XU4 embedded board from HardKernel™

##Board Detail
![ScreenShot](images/oCam_layout.png)


##Specifications
Type | Description |
------|------|
**Sensor** | OmniVision OV5640 CMOS Image sensor |
**Interface** | USB 3.0 |
**Lens** | Standard M12 Lens with focal length of 3.6mm (optional – 4mm, 8mm, 12mm) | 
**Supported OS** | Windows7, Windows8, Windows10, Linux, Plug-and play by UVC(USB Video Class) compliant | 
**Power** | USB Bus Power | 
**Operation Temperature** | 0°C ~ + 70°C |
**Rating** | DC 5V/290mA |
**Shutter** | Electric Rolling Shutter |
**Field Of View(FOV)** | 65deg. |
**Camera Control** | Brightness, Contrast, Hue, Saturation, White Balance | 
**Frame Rate** | **YUV** 1920x1080@15fps, 1280x720@30fps, 640x480@30fps<br/> **MJPEG** 1920x1080@30fps, 1280x720@45fps, 640x480@30fps<br/> **※For further details, please refer the release note at [this page](Firmware)** | 
**Weight** | 30.5g | 
**Size** | 42mm x 42mm | 

##oCam Packaging and Labeling
![ScreenShot](images/oCam_unpacking.png)


##oCam-Viewer (for Linux)
[![ScreenShot](images/oCam_viewer.png)](https://youtu.be/3x4ODTUOSds)
Detailed description is [here](oCam_viewer).

##Application: HandGesture
[![ScreenShot](images/oCam_handgesture.png)](https://youtu.be/qt8iNjDMUUo)
Detailed description is [here](https://www.youtube.com/watch?v=th8hUD7Ajg4)

#### modifications
* Change color based hand segmentation method to background difference method
* Add a trackbar for the threshold value of difference image
* Add an exception process for the empty data frame
* Add an exception process for the no-palm detection
* Comment out saving result image
 
#### How to build
* Refer to the attached [Makefile](HandGesture/Makefile)

##MotionEye OS - Video surveillance system
* MotionEye OS(oCam + odroid XU4) 
[![ScreenShot](images/motionEyeOs-odroidXU4.JPG)](https://youtu.be/ePXZSQPnM0Q)

* MotionEye OS(oCam + raspberryPi2) 
[![ScreenShot](images/motionEyeOs-RaspberryPi2.JPG)](https://youtu.be/ImZ8hTkd2R8)

Detailed description is [here](https://github.com/ccrisan/motioneyeos)

##Tutorial
Detailed description is [here](Tutorial)
