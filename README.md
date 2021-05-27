# CNC RobotPlotter using Cpp 

Mini CNC 2D plotter 

**Hardware:**
-1 X ARDUINO
-1 X L293D MOTOR SHIELD
-1 X SERVO MOTOR (TOWER PRO 9G)
-JUMPER WIRES
-SOME HARDWARE NUT BOTS ETC

![image](https://user-images.githubusercontent.com/24978535/119817072-23236600-bf0b-11eb-9d0e-7ec6c0ad6a5d.png)

**Softwares used:**


- Arduino IDE

- Processing IDE Program (GCTRL)

- To make gcode files that are compatible with this cnc machine you have to use the Inkscape.

https://inkscape.org/en/download/windows/
Note**
(Important: download 0.48.5 version)
Now you need to install an Add-on that enables the export images to gcode files. This add on can be found here with installation notes.

https://github.com/martymcguire/inkscape-unicorn

**Processing Gcode in Arduino: **

1> upload the code to arduino using arduino IDE .ino file

2> Generate sample Gcode

3>Upload the gctrl file to processing IDE
and click on PLAY button in processing window.
first press 'p' to select you com port
if you want you can set jog speed by pressing 1,2, or 3 button from keyboard
press 'g' to load G-code file
your machine is ready to plot as soon as you hit enter by selecting g code file
now you have done your plotter is ready

