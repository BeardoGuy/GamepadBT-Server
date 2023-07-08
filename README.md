# GamepadBT-Server
Server program/app to communicate with the Nokia N-Gage Symbian S60 [GamepadBT](https://github.com/BeardoGuy/GamepadBT) App over Bluetooth.  
[GamepadBT](https://github.com/BeardoGuy/GamepadBT) is a Project to convert Symbian Series60 mobile into a Bluetooth Gamepad specifically the Nokia N-Gage and N-Gage QD.  

![Screenshot](https://github.com/BeardoGuy/GamepadBT-Server/blob/main/Screenshots/Screenshot%202023-07-08.jpg?raw=true)  

This GamepadBT-Server program runs on Windows and connects to the N-Gage over Bluetooth directly without any external hardware dongle as required earlier.  
It can now use the PC's inbuilt Bluetooth or USB Bluetooth Adapter to enable the Nokia N-Gage keystrokes as received via the GamepadBT app to act as native Windows Keyboard keystrokes so that you can play PC games and Emulator such as [EKA2L1](https://github.com/EKA2L1/EKA2L1) directly with the N-Gage acting as a Gamepad/Joystick.  

* The Program will only work if your N-Gage/Symbian device can connect to your PC over Bluetooth normally and can transfer files without error. Some modern inbuilt Bluetooth adapters cannot connect to these older Symbian devices, so please try to pair and send a file before using.

# Usage:  
* Download the GemepadBT-Server program from the [Releases](https://github.com/BeardoGuy/GamepadBT/releases/)  
* Select the COM port in the list according to the port your PC uses to connect to your N-Gage/Symbian device (Under Windows 10 and 11 you can find that by going to Settings -> Bluetooth Settings-> More Bluetooth settings -> COM Ports Tab and then check which COM Port is labeled as 'Incoming' for your N-Gage/Symbian Device.)  
* Select the BAUD Rate (9600 is the most compatible and 115200 is the fastest)  
* Click on 'Connect" button and wait until the 'Status:' changes to 'Server Started' (If any error pops up, try another Port)  
* Now open up the GamepadBT app on N-Gage and Connect to your PC. It should start working right away.  

* Open up the EKA2L1 Emulator or a Game that you want to play and go to the Keyboard key settings and map the keys however you want.
