OscillTrack - Real-time brain activity tracking and adaptive stimulation.

OscillTrack tracks oscillatory activity of a defined frequency in real-time. It provides a complex estimate of the signal within a frequency band of interest and from this the instantaneous phase and amplitude. It can be used to trigger stimulation. Please cite [McNamara et al. (doi.org/10.1101/2021.10.14.464387)](https://doi.org/10.1101/2021.10.14.464387) in publications that avail of this general method of oscillatory tracking. Further information is available in the publication.

### Download

OscillTrack code download is available for academic use [here](https://process.innovation.ox.ac.uk/software/p/15929/oscilltrack-academic/1).

We provide floating-point microcontroller code tested on Teensy 4.0 clocked at 24 MHz and Teensy LC Arduino compatible 32 bit ARM Cortex-M series (M7 and M0 respectively) microcontroller boards. This code can be adapted for use in a wide range of settings.  The Teensy 4.0 can accommodate higher sample rates whereas the maximum sample rate with the Teensy LC is 1k without serial port active and 625 with serial port active.

We also provide a fixed precision digital circuit hardware description of OscillTrack in Verilog, which was implemented on an FPGA to conduct the experiments described in [McNamara et al.](https://doi.org/10.1101/2021.10.14.464387)
