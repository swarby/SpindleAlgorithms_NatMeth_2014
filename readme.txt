SpindleAlgorithms_NatMeth2014

This archive is the code for the spindle detection algorithms described in:

Warby SC, Wendt SL, Welinder P, Munk EGS, Carrillo O, Sorensen HBD, Jennum P, Peppard PE, Perona P, Mignot E. Sleep-spindle detection: crowdsourcing and evaluating performance of experts, non-experts and automated methods. Nat. Methods 2014 Apr;11(4):385–392.

Detectors A1-A6 as Matlab code:

a1_spindle_detection.m.txt 
a2_spindle_detection.m.txt 
a3_spindle_detection.m.txt 
a4_spindle_detection.m.txt 
a5_spindle_detection.m.txt 
a6_spindle_detection.m.txt

These files can be opened with a text editor to view, but require MATLAB software to run (http://www.mathworks.com/products/matlab/)

Remove the .txt extension from the files to convert them to .m scripts needed for Matlab.

## Update 2018-07-07
The code for two detectors (A3 and A4) has been updated to a3_spindle_detection_v02.m.txt and a4_spindle_detection_v02.m.txt.

A3
There was an error in the calculation of the background NREM signal that is used to establish the threshold.  The NREM background window was much shorter than required.  Performance of this detector (relative to the human consensus) has been improved due to this fix.

A4
Small discrepencies between the original C implementation and this implemenation have been fixed.  The changes only have a small impact on the performance (relative to the human consensus) of this detector.

The original implementations of both A3 and A4 can be found in the originalCode_2014.zip archive file.

## For any questions or comments, please contact Simon Warby (simon.c.warby@umontreal.ca)

