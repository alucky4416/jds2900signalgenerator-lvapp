LabVIEW application for JDS-2900 Signal Generator (UNOFFICIAL)
=================================================

# Overview
  This LabVIEW application(not driver) is that can be remote control
  JDS-2900 via USB(virtual COM port).
  You can change the values of Wave Type, Frequency, Amplitude, Offset and Duty.
  Unfortunately, not supported turn on/off output signal.
  This software is ** UNOFFICIAL.**
  ** Please do not ask the manufacturer or seller about this software.**

# Requirements
  * Windows(7/8/10) PC with USB port (Type A)
  * ** LabVIEW 2014 or later **
  * ** NI-VISA 14.0 or later **

# Start
 * Download souce (https://github.com/alucky4416/jds2900signalgenerator-lvapp/)
 * JDS-2900 connect to PC via USB.
 * Power ON JDS-2900
 * Check COM port number(ex. COM3 or COM4) from Device and Interface on the NI-MAX.
 * Launch LabVIEW and open LvJDS2900SignalGeneratorApp.lvproj from source files
 * Open ** LvJDS2900SignalGeneratorApp.vi **
 * ** Enter COM port number.**
 * Press Run button

# License
 MIT
