# GPGPU-sim_express_edition
Download into virtual machine (ubuntu 14.04 on my desktop) &amp; just run with it. Skip the steps of installing SDK, ispass2009-benchmarks and gpu driver.

## Step1: 
Install those necessary packages like gcc/g++ and CUDA4.2. No need to install SDK or gpu driver. See other details on gpgpusim [github](https://github.com/gpgpu-sim/gpgpu-sim_distribution).

## Step2: 
Download this repository and run "source setvar.sh" in terminal.

## Step3: 
Download the gpgpusim repository and copy out config folder into your working path.

## Step4: 
Copy your executable file (compiled by nvcc) into the config folder (eg. GTX480) and run "./\<your ex file name\>".
