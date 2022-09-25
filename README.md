DjiMini2RCasJoystick
===============
 - Connect your DJI Remote Controller to your PC and use it to play simulators
 - Currently confirmed working controllers: DJI Mini 2 RC (also known as RC-N1, RCS231, WM161b-RC-N1, RCN1)
 - inspired by (actually improved and modified for Mini 2 RC) [justin97530/miniDjiController](https://github.com/justin97530/miniDjiController) and [usatenko/DjiMini2RCasJoystick](https://github.com/usatenko/DjiMini2RCasJoystick)
-----------------------------------------------------------------------------

to run it
- install dependencies (you may need to install them under sudo)
- connect your RC via usb connector to your laptop
- configure and enable virtual joystick with vJoy (https://sourceforge.net/projects/vjoystick/)
- run "sudo python3 main.py -p COM3"
- your RC will be set to simulator mode and it will pass stick values to virtual joystick

Note: DJI Fly Simulator only accepts XBox controllers but you can emulate one with https://www.x360ce.com/

DJI RC via USB -> DjiMini2RCasJoystick -> VJoy -> X360CE -> DJI Flight Simulator
