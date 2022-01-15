# colourdetect-maxmsp
V3 
* I made some adjustments to make it more accurately detect the colours (for the samples that I am using). V2 was having some issues where if I lifted the Red sample away from the TCS34725 RGB colour sensor, it would falsely trigger the Green. This appears to be fixed (or at least happens less often) with V3. 

V2
* V2 is a Max MSP bpatcher converts RGB values to HSL. Then the H is mapped to MIDI values. It is a much better method to detect the colours than before.
* I use this patch with a TCS34725 RGB sensor. But this bpatcher my be adapted to use other RGB data inputs from a USB camera or video. 
* Inside the bpatcher is an "i" icon. Click that to read more details on how the bpatcher works. 

V1 (ColourDetect_MaxPatch)
* V1 is A Max MSP bpatcher that compares incoming RGB values to stored values and outputs the name of the closest approximation for what the colour is.
* I initially used it for a TCS34725 RGB sensor. But this bpatcher my be adapted to use other RGB data inputs from a USB camera or video. 
* Inside the bpatcher is an "i" icon. Click that to read more details on how the bpatcher works. 
* Most important thing to remember is you have to sample the colours before you start using the bpatcher for version 1. This is not necessary in V2.

If you experience any issues or have any questions, let me know: www.chantelleko.com
