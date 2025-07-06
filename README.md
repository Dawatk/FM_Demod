# FM_Demod
This is a basic FM radio receiver I built using GNU Radio and a USRP B205mini-i. Instead of using GNU Radio's high-level WBFM Receive block, I wanted to manually construct the signal chain from lower-level DSP blocks — both to better understand how FM demodulation works and to give myself more control over each stage of the process.

The flowgraph receives live broadcast FM signals, filters and demodulates them, and sends the resulting audio to my computer speakers in real time. I've also worked on a simple GUI to tune stations, adjust volume, and visualize the signal spectrum.

# Future Plans:
  Add station scanning and presets
  
  Add squelch/mute options
  
  Possibly record audio to a file



