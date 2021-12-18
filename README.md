# RPCS3 Sinden Lightgun Time Crisis - Rising Storm for Launchbox

##Description 
This script is made for use with launchbox, Emulator settings autohotkey start script.

##Features
* Hide Mouse from Scroll Lock key
* Auto Change Resolution to 1920X1080 to have consitent results and work on ultrawide monitors
* Auto Maximize and Hide RPCS3 status bar
* Auto Enable Sinden Bars
* Exit Script to return to old resolution

##Requirements
Launchbox
Creating a New Emulator for RPCS3 (as it bind the AHK scrip for each emulator)

##Custom Emulator Settings
  Start games in fullscreen mode: false

Video:
  Write Color Buffers: true

Input/Output:
  Keyboard: "Null"
  Mouse: Basic
  Camera: Fake
  Camera type: PS Eye
  Camera flip: None
  Camera ID: Default
  Move: Mouse
  Buzz emulated controller: "Null"
  Turntable emulated controller: "Null"
  GHLtar emulated controller: "Null"
  
Miscellaneous:
  Exit RPCS3 when process finishes: true
  Start games in fullscreen mode: false

##Custom Controller Settings
  Handler: Keyboard
  Device: Keyboard
  Config:
    Start: N
    Select: B
