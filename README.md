# Polar codes
This repository is devoted to the Python implementation of basic polar codes.

## Motivation
Originating from the final course work (TCC).
Author: Luiz Fernando de Sousa Vaz Rangel.
Project Title: Implementation of Polar Codes in Python (Implementação de Códigos Polares em Python).
This is  open-source project.
Comments, remarks and pull requests are welcome!


## It provides
 - a non-systemic encoder.
 - non-recursive implementations of the successive cancellation decoder (SCD).
 - construction of polar codes using Gaussian Approximation
 - an AWGN channel with BPSK modulation.
 
## What is inside

Currently this repository is work-in-progress. 
In particular, the following funcionalty is implemented, but comments are still are to be written and some features shall be tested.

 It has the following functions.
    - [x] **construct** — Polar codes are channel-dependent and thus they can be constructed in many ways.
    - [x] **encode** — implements encoding algorithm which complements informational bits with frozen ones and applies a polar transform to the resulting codeword.
    - [x] **decode** — up to now there are several decoders proposed for Polar codes which have different computational efficiency and error-correction ability.
    This method simply call a specified decoder
        - [x] **Successive Cancellation (SC)** — a simple successive-cancellation decoder initially proposed by Arikan. 
        **Thorough testing is required**!
- [x] **simulation** — an implemetation of monte carlo for case of AWGN channel combined with BPSK.

All algorithms are based on papers, references to them will be added further.

## How to use

The notebook is "polarcodes_V01.ipynb".
Thus, you may copy it and execute it in google colab.
Probaly, it is not as pretty as one may want and I will fix it further.