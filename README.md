# Kafka-DLP-Printer
*“the blend of absurd, surreal and mundane which gave rise to the adjective "kafkaesque”*

A 3d resin printer based on the Cristelia printer and a few others. Discovering all the details needed to make this printer was a maddening process that involved, a japanese company, people from the uk, germany and poland, a mexican company and a non zero sum of going down rabbit holes. The goal of this project is to try to provide a detailed process that others can follow with less effort than what I had to put into getting this to work.


# A post mortem 

### What went wrong:

To put it simply, this printer was complete on the hardware side, but the software side made it impossible. The issue is with so many different components, a raspberry pi 3, an adafruit experimental board, and a ipad screen, the control system was very glitchy. Motors would burn out, the screen never displayed correctly. Nanodlp is not a software suite designed for easy to modify coding, even getting it to run on an Raspberry pi proved difficult. Some weren't supported, the wifi glitched out, everything tended to have problems. 

### What went wrong:

My next step is to create my own 3d printer from scratch using custom firmware and software, I firmly believe that there is a way to create a cheap, useful sla printer using other avenues of research. From what I can gather using cell phone screens is risky as they can be unreliable, but mostly they are expensive and hard to connect to. Simplifying it to use standard gcode would make everything so much smoother. I am mostly done with the new version, however I am trying to start a company with it so stay tuned to see if I get funding!

### What is this:

This is a daylight resin printer based off of the excellent design of the Cristelia 3d printer, a lot of the files have been reused without modification however some had to be modified to suit my needs. Such as making the lead screw the much easier to find 8mm, switching the corner supports to square tubing in order to save money. Using an off the shelf nema to lead screw adapter. 

### Parts
* Raspberry pi 3 with wifi
* 1 servo motor
* RAMPS board with arduino
* Ipad 3/4 display
* Ipad display driver
* Hacked 120vac to 12/5vdc adapter


### Inspiration

* http://www.instructables.com/id/RooBee-One-SLA-DLP-Aluminum-Frame-3D-Printer/
* https://www.thingiverse.com/thing:1680172
* https://www.thingiverse.com/thing:2216068
