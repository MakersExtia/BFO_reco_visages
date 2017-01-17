#!/usr/bin/env python
import camera
import time

camera=picamera.PiCamera()

camera.start_preview
time.sleep(10)

camera.capture('/home/pi/desktop/img.jpg')
camera.stop_preview()
