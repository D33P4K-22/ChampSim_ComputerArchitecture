# ChampSim Branch Predictor & Cache Replacement Study

ChampSim simulator modifications and evaluations, built as a Computer Architecture assignment.

## What it does
- **Branch prediction:** Implements a Modified Bullseye predictor with an adaptive threshold,
  cutting branch mispredictions by 38% and raising prediction accuracy to 98.3% on SPEC CPU2017 traces.
- **Cache replacement:** Implements and compares custom LLC replacement policies — MRU, Random, and
  a custom Hard-to-Cache (HCIT) policy using XOR-hashed PC tracking with RRIP-based protected block insertion.

## Tech
C++, ChampSim simulator, SPEC CPU2017 traces

## Status
Completed as a Course Project; results evaluated against baseline ChampSim predictors and replacement policies.
