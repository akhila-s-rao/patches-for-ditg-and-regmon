# patches-for-ditg-and-regmon
This repository contains bug fixes and patches to open-source tools and software to enable high-fidelity wireless measurements. 
D-ITG is a traffic generator and the patch created is necessary for correct measurements of packet delay when RTTM or round trip time mode of the traffic generator is enabled.
Regmon is a tool to log the different states of the wifi interface and report on how much time it spent in each state by logging the state periodically. While the log generation script was okay, there was a bug in the script that print out the time spent in each state whih has been fixed.    
