# Sparsity-aware-Sphere-Decoding
This repository contains scripts for running the sparsity-aware sphere decoding algorithm. Please refer to this paper for algorithmic details. If you plan to use Sparsity-aware Sphere Decoding Algorithm in your academic projects, please cite the paper mentioned below. 

Citation: "Barik, Somsubhra, and Haris Vikalo. "Sparsity-aware sphere decoding: algorithms and complexity analysis." IEEE Transactions on Signal Processing 62.9 (2014): 2212-2225."

## Files 
master.m
runSDsparse.m
SDsparsecmplxty.m
combn.m
sparse_constellation.m

## Installation 
Download all the files in a local directory SRC. Start MATLAB and navigate to SRC. Run the script by typing the command : 
[simu, theo, biterr] = master_latest(rx,tx,k,k_rx,L,snr,runtime,maxexpand) 

Sample Command : 
[simu, theo, biterr] = master_latest(20,20,5,5,2,5,100,10) 
