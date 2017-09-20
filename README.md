Parameters Calibration on CT System

Computed tomography (CT) is a well-known imaging technique for nondestructive detections of inner structure for biological tissues and engineering materials. By utilizing the energy absorptions of the detected samples for incident X-rays, this technique can reconstruct the sample parameters from energy absorption data corresponding to incident X-rays along many directions. A typical two-dimensional CT system is shown in Figure 1. The parallel incident  X-rays, which are always vertical to the detector, are injected from different directions. We consider each receiver on the detector as a point, and all the receivers are located with equidistance. When this transmitter-receiver system rotates counter-clockwise 180 times around a fix point, the energy absorptions measured at all the receivers for the motionless sample located between the transmitter and the detector reveal the interior structures of the sample detected. These data acquisition processes are carried out from 512 receivers located on the detector corresponding to 180 different incident directions of parallel X-rays.

However, there are always some errors in the CT system during installations, leading to the errors for the CT parameters, which influences the imaging quality. Therefore parameters calibration on CT system is necessary by using some special known phantoms, before this CT system can be put into practical use.

Please establish the mathematical model, as well as the corresponding algorithms for the above imaging process, to solve the following problems:

1. Assume that the known phantom for parameters calibration consists of two homogeneous solid media placed on a square pallet. The geometric configuration of the phantom measured by millimeter is shown in Figure 2 with the corresponding data file given in Appendix 1, where the values defined on every pixel represents the absorption intensity of this unit, which are called "absorptivity" here. The corresponding energy absorption quantities for this phantom are given in Appendix 2. Using the provided data, determine the rotation center of CT system, the distance between two adjacent receivers, and all the 180 incident directions of X-rays.

2. In Appendix 3, the energy absorption values from the above CT system for some unknown sample are given. Reconstruct the sample parameters such as geometric configurations of the sample on the square pallet, and the absorptivity distribution of this sample, utilizing the calibrated parameters generated in (1). In addition, give the absorption values at 10 points shown in Figure 3, the locations of these ten points are specified in Appendix 4.

3. In Appendix 5, the energy absorption values from the above CT system for another unknown sample are given. Provide the information of this unknown sample, utilizing the calibrated parameters given in (1). In addition, please give the absorption values at 10 points shown in Figure 3.

4. Analyze the accuracy and stability of parameter calibration based on the phantom given in (1). Then design a new phantom and set up corresponding calibration model and algorithm to improve the accuracy and stability of parameters calibration. Present your reasons.

All numerical results for (1)-(4) are retained by 4 decimal places. Please provide your reconstructions for (2)-(3) by data files with the size 256 × 256 in the same format as Appendix 1. Two files should be named as “problem2. xls” and “problem3. xls”, respectively.
