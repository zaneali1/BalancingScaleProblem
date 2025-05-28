# Balancing Scale Problem

A solution to the **Balancing Scale Problem**, where a tree of interconnected weighing scales must be balanced by determining the minimal additional mass needed on each pan.

## Problem Overview

Each scale weighs 1kg and may hold:
- A mass,
- Another scale,
- Or both.

Input is provided via `System.in` and represents a tree of such scales. The goal is to output the additional mass needed on each pan to perfectly balance every scale.

## Example
**Input:**
B1,10,B2
B2,B3,4
B3,7,8

**Output:**
B1,25,0
B2,0,13
B3,1,0

## Solution Highlights

- **Memoisation** used to avoid redundant computation.
- Outputs minimal added weights per scale in input order.

## Run

Compile and run with input from `System.in`
