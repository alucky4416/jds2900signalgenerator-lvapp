LabVIEW application for JDS-2900 Signal Generator (UNOFFICIAL)
=================================================

# Overview
  This LabVIEW application is that you can be to remote control JDS-2900 via USB(virtual COM port). It is not a VI driver/Library.
  You can remotely control the wave type, frequency, amplitude, offset, and duty.  
  This software is **UNOFFICIAL.**  
  **Please do not ask the manufacturer or seller about this software.**  

# Requirements
  * Windows(7/8/10) PC with USB port.  
    This software requires the USB serial driver to be installed. It is included in the CD that came with the JDS2900.  
  * **LabVIEW 2014 or later**
  * **NI-VISA 14.0 or later**

# Get started
 * Download source ( https://github.com/alucky4416/jds2900signalgenerator-lvapp.git )
 * JDS-2900 connects to a PC with a USB cable.
 * Power ON JDS-2900
 * Check COM port number(ex. COM3 or COM4 or ..) from Device and Interface on the NI-MAX.
 * Launch LabVIEW and open LvJDS2900SignalGeneratorApp.lvproj
 * Open **LvJDS2900SignalGeneratorApp.vi**
 * **Enter COM port number (COM3 or COM4 or ..)**
 * Press the Run button on the LabVIEW toolbar.

# License
 MIT
