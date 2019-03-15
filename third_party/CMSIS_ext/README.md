# TFLiteMicro_CustCMSIS
Custom CMSIS files needed for TFLiteMicro examples
# Description of files

* **arm_cmplx_mag_squared_q10p6.c**: Modified version of the ARM CMSIS function [arm_cmplx_mag_squared.c](http://arm-software.github.io/CMSIS_5/DSP/html/group__cmplx__mag__squared.html#ga45537f576102d960d467eb722b8431f2). The modification is that we have changed the amount of right-shift to make sure our data is in the correct range. We redistribute because the original content was created with the Apache 2.0 license.
* **arm_cmplx_mag_squared_q10p6.h**: Header file for arm_cmplx_mag_squared_q10p6.c
