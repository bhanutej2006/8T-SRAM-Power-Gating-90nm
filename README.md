# 8T SRAM Design Using Footer Sleep Transistor

## Project Overview

This project focuses on designing and analyzing an 8T SRAM cell using a footer sleep transistor-based power-gating technique.

The main objective is to reduce standby leakage power while maintaining data retention and acceptable read/write performance.

## Technology Used

* Technology: 90 nm CMOS
* Technology Library: gpdk090
* EDA Tool: Cadence Virtuoso
* Simulation: Transient and DC analysis

## Design Description

A footer NMOS sleep transistor is connected between the SRAM cell and ground.

It operates in two modes:

* Active mode: Sleep transistor ON.
* Standby mode: Sleep transistor OFF.

## Performance Parameters

* Average power
* Standby leakage
* Read delay
* Write delay
* Data retention
* Static Noise Margin

## Results

The case study investigates the reduction in standby leakage and the associated timing and data-retention trade-offs.

## Documentation

The complete case study PDF is available in this repository.

## Future Work

* Footer transistor sizing optimization
* Header versus footer comparison
* SRAM array implementation
* Post-layout verification
