# colourdetect-maxmsp
V5 
* I was doing some testing with both paint chips and with fabric that had fabric paint on them. I worked on getting the patch the most accurate when using either method and while using all colours available. It was really tricky for it to recognize the difference between orange and red, but I think I have it as close as it is going to get now. I noticed that the "clear" threshold is best set to 850 while using paint chips, and 1000 while using the fabric paint swatches. 

V4 
* In the previous versions the values that I was receiving were well over 500. But I figured out why and now I am only receiving RGB values up to 255, which is typical for colour. So the patch is adjusted accordingly for that. 

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

If you experience any issues or have any questions, please let me know: https://www.chantelleko.com/contact.html
