# Source
https://www.eduke32.com/
https://wiki.eduke32.com/wiki/EDuke32 is the official EDuke32 documentation resource.

# How to build
`make -j6 USE_OPENGL=0 SDL_TARGET=2 USE_LIBVPX=0`

# Configuration
`~/.config/eduke32/eduke32.cfg`

```
[Screen Setup]
Polymer = 1
ScreenBPP = 8
ScreenHeight = 480 // change to 320 (or delete line) for RG351P
ScreenMode = 0 // retain = 0 for RG351P; GameForce Chi can use = 1
ScreenWidth = 640 // change to 640 (or delete line) for RG351P

[Controls]
AutoAim = 1
ControllerAnalogAxes0 = "analog_strafing"
ControllerDigitalAxes0_0 = ""
ControllerDigitalAxes0_1 = ""
ControllerAnalogScale0 = 65536
ControllerAnalogInvert0 = 0
ControllerAnalogDead0 = 1000
ControllerAnalogSaturate0 = 32768
ControllerAnalogAxes1 = "analog_moving"
ControllerDigitalAxes1_0 = ""
ControllerDigitalAxes1_1 = ""
ControllerAnalogScale1 = 65536
ControllerAnalogInvert1 = 0
ControllerAnalogDead1 = 1000
ControllerAnalogSaturate1 = 32768
ControllerAnalogAxes2 = "analog_turning"
ControllerDigitalAxes2_0 = ""
ControllerDigitalAxes2_1 = ""
ControllerAnalogScale2 = 29491
ControllerAnalogInvert2 = 0
ControllerAnalogDead2 = 1000
ControllerAnalogSaturate2 = 32768
ControllerAnalogAxes3 = "analog_lookingupanddown"
ControllerDigitalAxes3_0 = ""
ControllerDigitalAxes3_1 = ""
ControllerAnalogScale3 = 13107
ControllerAnalogInvert3 = 0
ControllerAnalogDead3 = 1000
ControllerAnalogSaturate3 = 16384
ControllerAnalogAxes4 = ""
ControllerDigitalAxes4_0 = ""
ControllerDigitalAxes4_1 = "Previous_Weapon"
ControllerAnalogScale4 = 65536
ControllerAnalogInvert4 = 0
ControllerAnalogDead4 = 2000
ControllerAnalogSaturate4 = 65536
ControllerAnalogAxes5 = ""
ControllerDigitalAxes5_0 = ""
ControllerDigitalAxes5_1 = "Next_Weapon"
ControllerAnalogScale5 = 65536
ControllerAnalogInvert5 = 0
ControllerAnalogDead5 = 2000
ControllerAnalogSaturate5 = 65536
ControllerAnalogAxes6 = ""
ControllerDigitalAxes6_0 = ""
ControllerDigitalAxes6_1 = ""
ControllerAnalogScale6 = 65536
ControllerAnalogInvert6 = 0
ControllerAnalogDead6 = 2000
ControllerAnalogSaturate6 = 65536
ControllerAnalogAxes7 = ""
ControllerDigitalAxes7_0 = ""
ControllerDigitalAxes7_1 = ""
ControllerAnalogScale7 = 65536
ControllerAnalogInvert7 = 0
ControllerAnalogDead7 = 2000
ControllerAnalogSaturate7 = 65536
ControllerAnalogAxes8 = ""
ControllerDigitalAxes8_0 = ""
ControllerDigitalAxes8_1 = ""
ControllerAnalogScale8 = 65536
ControllerAnalogInvert8 = 0
ControllerAnalogDead8 = 2000
ControllerAnalogSaturate8 = 65536
ControllerButton0 = "Open"
ControllerButtonClicked0 = ""
ControllerButton1 = "Jump"
ControllerButtonClicked1 = "Jetpack"
ControllerButton2 = "Toggle_Crouch"
ControllerButtonClicked2 = ""
ControllerButton3 = "AutoRun"
ControllerButtonClicked3 = "Holo_Duke"
ControllerButton4 = "Third_Person_View"
ControllerButtonClicked4 = "Toggle_Crosshair"
ControllerButton5 = ""
ControllerButtonClicked5 = ""
ControllerButton6 = ""
ControllerButtonClicked6 = ""
ControllerButton7 = "Map"
ControllerButtonClicked7 = ""
ControllerButton8 = "Center_View"
ControllerButtonClicked8 = ""
ControllerButton9 = "Alt_Fire"
ControllerButtonClicked9 = ""
ControllerButton10 = "Fire"
ControllerButtonClicked10 = ""
ControllerButton11 = "Map_Follow_Mode"
ControllerButtonClicked11 = ""
ControllerButton12 = "Inventory"
ControllerButtonClicked12 = ""
ControllerButton13 = "Inventory_Left"
ControllerButtonClicked13 = ""
ControllerButton14 = "Inventory_Right"
ControllerButtonClicked14 = ""
ControllerButton15 = ""
ControllerButtonClicked15 = ""
ControllerButton16 = ""
ControllerButtonClicked16 = ""
ControllerButton17 = ""
ControllerButtonClicked17 = ""
ControllerButton18 = ""
ControllerButtonClicked18 = ""
ControllerButton19 = ""
ControllerButtonClicked19 = ""
ControllerButton20 = ""
ControllerButtonClicked20 = ""
MouseButton0 = "Fire"
MouseButton1 = "MedKit"
MouseButton2 = "Jetpack"
MouseButton4 = "Previous_Weapon"
MouseButton5 = "Next_Weapon"
MouseAnalogAxes0 = "analog_turning"
MouseAnalogAxes1 = "analog_moving"
MouseButtonClicked0 = ""
MouseButtonClicked1 = ""
MouseButtonClicked2 = ""
MouseButton3 = ""
MouseButtonClicked3 = ""
MouseButtonClicked4 = ""
MouseButtonClicked5 = ""
MouseButton6 = ""
MouseButtonClicked6 = ""
MouseButton7 = ""
MouseButtonClicked7 = ""
MouseButton8 = ""
MouseButton9 = ""

[Comm Setup]
PlayerName = "Duke"
RTSName = "DUKE.RTS"
CommbatMacro#0 = "An inspiration for birth control."
CommbatMacro#1 = "You're gonna die for that!"
CommbatMacro#2 = "It hurts to be you."
CommbatMacro#3 = "Lucky son of a bitch."
CommbatMacro#4 = "Hmmm... payback time."
CommbatMacro#5 = "You bottom dwelling scum sucker."
CommbatMacro#6 = "Damn, you're ugly."
CommbatMacro#7 = "Ha ha ha... wasted!"
CommbatMacro#8 = "You suck!"
CommbatMacro#9 = "AARRRGHHHHH!!!"
```

`~/.config/eduke32/settings.cfg`
```
in_joystick "1"
crosshair "1"
```
