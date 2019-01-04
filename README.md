# node-red-security-cam
A complete security camera system build with Raspberry Pis and Node Red.
Over the years I havve tried many brands of IP cameras.  Each brand tries to vendor-lock you into their software.  Ever IP camera is different. I consider them a security risk since you don't really have access to the operation system they are running.  You cant integrate them into your home automation very well.
There are some great open source securtity camera progams out there that do well to integrate branded cameras but it can be a mojor pain as each camera has hard-to-find settings to access their video stream.  
Using Raspberry Pi boards runinng MotionEyeOS or Raspbian with Motion installed, you can easily access the video stream.  You can then run a browser based 'server' with Node Red that shows you all of your camera feeds, interacts with any home automation projects and manages all the Pi boards on your network.
