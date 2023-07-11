# LTPOnline <span style="font-size: 10pt">a script for CED Signal software</span> 

## Installation
This script reqires [Signal 6.0](https://ced.co.uk/products/signal) or higher.  
Copy the scipt folder in any directory and open the **LTPonline.sgs** file using Signal.

## Online Use
Load your sampling configuration then run the script. Adjust the SETTINGS to your liking. Press START to start sampling with the loaded configuration. The script will automatially create a plot for fiber volley, amplitude and slope.

## Changelog
* 1.53b
  - fixed Analysis taking the wrong amounts of frames for averages, changes to SamplingInterval  
* 1.52b
  - fixed online sampling  
* 1.51b
  - fixed a bug that would crash the script when analyzing files where only higher FrameStates or Channels where used (e.g. Ch2 and State 2 but not Ch1 and State 1)  
* 1.5b
   - multiple response channels: Channel select dialog allows to select multiple response channels  
* 1.42b
  - Added button to load config files  
  - Added button to save config files  
* 1.41b
  - Added saving cursor positions for each frame state  
  - Added manual cursor positioning /need: save cursor positions for each frame state  
* 1.4b
  - Refactored new LTPOnline Script  




  

