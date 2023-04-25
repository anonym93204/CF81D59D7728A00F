# FairTQ-Exact: Fair Top-k Query on Alpha-Fair

This repository contains the code and the technical report for the submission "FairTQ-Exact: Fair Top-k Query on Alpha-Fair".

## Requirements
- Linux Environment with GCC

## Usage

1. Download this repository

2. Change the working direction into FairTQ-Exact/.

3. Compile with "make" command.

    - This will automatically compile the dependency package qhull under qhull/ and compile our main code under UTK/.

4. Run our tests with "./run_all_tests.sh".

    - This will run two tests under folder test1/ and test2/, using dataset XING and COMPAS, respectively.
    - For both tests, the exact algorithm FairTQ-Exact will first be executed, and then follows the approximation algorithm beta-FairTQ-Approx.
