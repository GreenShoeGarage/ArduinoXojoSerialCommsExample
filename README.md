# Arduino+Xojo: A Serial Communications Example
 
This is a quick and dirty example of how to connect an Arduino dev board, via a USB cable, to a Windows desktop application built using Xojo (a "Cross-platform App Development Tool").

My goal was to achieve the following goals:

- Connect to an Arduino, by selecting the Arduino from a list of COM ports.
- Read from the serial port (in this example, the A0 analog input pin)
- Toggle a LED on the Arduino, by writing an "H" or "L" to the serial port
- Write a date-time stamp and the analog pin value to a .CSV file locally on the computer


There are three subfolder under the "Software" folder:

- "Arduino Firmware": Contains the .ino file that can be edited and flashed to your Arduino
- "Xojo Project": The raw Xojo project file that can be edited to meet your needs
- "Windows Executable": A .exe file that can be ran on a Windows 10 machine, as-is



Word of Warning: This code is provided as-is. It is experimental and not fully tested. Use at your own risk, and do NOT use for any production or other critical applications. You have been warned!
