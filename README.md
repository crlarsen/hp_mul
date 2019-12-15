# Verilog IEEE 754 16-bit Binary Multiply Operator

## Description

Simple implementation without support for rounding results.

Code is explained in the video series [Building an FPU in Verilog](https://www.youtube.com/watch?v=rYkVdJnVJFQ&list=PLlO9sSrh8HrwcDHAtwec1ycV-m50nfUVs).
See the videos *Building an FPU in Verilog: Build the Multiplier, Parts 1, 2, & 3*.

## Manifest

|   Filename   |                        Description                        |
|--------------|-----------------------------------------------------------|
| hp_mul.v     | Main module for the multiply operator                     |
| hp_class.v   | Utililty module used by hp_mul module to compute value type and extract the exponent and significand fields |
| hp_mul_tb.v  | Verilog testbench code                                    |
| simulate.log | Output from testbench simulation run using Vivado         |
| README.md    | This file                                                 |

## Copyright

:copyright: Chris Larsen, 2019
