### DDoS-detection-using-Entropy-computing
<p>From the results it is noticed that the Entropy based detection algorithm detects lower than threshold Entropy values and block attack packets and only keep normal packets.</p>
#### IMPLEMENTATION:
<p>Entropy based detection algorithm has been implemented in Ubuntu 14.04 (64-bit) operating System (Virtual Machine) which is installed in Virtual Box with 5000 MB base memory; and a package of Mininet was installed in this virtual machine as the emulation tool. Mininet is a network emulator.
The controller in which the algorithm was run is POX; POX is an open source controller written in python programming language.
The l3_learning module in POX controller has been modified by importing the DDoS detection class(where entropy of packets has been calculated and compared with Threshold value) from entropyCalculation module;
</p>
 
