# Experiments Data

This repository contains the benchmark datasets and experimental results used in our paper.  
The result data can be validated using binary files provided by the industrial vendor, ensuring both correctness and authenticity.

## Contents
- `input/` : Benchmark testcases from the ICCAD 2019 CAD Contest.
- `LD_result/`  
  Contains the outputs of  ** the Lagrange decomposition algorithm**.  

- `Greedy_result/`  
  Contains the outputs of ** the greedy algorithm**.  
  These results serve as a baseline, allowing direct comparison to highlight the contribution of rerouting.

- `evaluater` : Binary tool provided by the competition organizers for result validation.

## How to Run

To validate the routing results, use the vendor-provided binary tool:

```bash
./evaluater ./input/synopsys01.txt ./LD_result/01_output
