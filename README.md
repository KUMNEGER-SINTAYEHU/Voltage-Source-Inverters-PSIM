# Voltage Source Inverters (VSI) Simulation

A suite of simulation models developed in PSIM to analyze switching strategies and harmonic mitigation in single-phase and three-phase inverters.

## Overview
This repository contains PSIM simulation files for single-phase H-bridge and three-phase full-bridge Voltage Source Inverters (VSIs). The project focuses on the comparative analysis of different pulse-width modulation (PWM) techniques and their direct impact on output power quality.

## Key Features & Analyses
* **Single-Phase H-Bridge VSI:** Comparison of Bipolar and Unipolar Sinusoidal PWM (SPWM) modulation strategies.
* **Three-Phase Full-Bridge VSI:** Evaluation of Six-Step control (180° conduction) versus three-phase SPWM.
* **Harmonic Mitigation:** Demonstration of how Unipolar SPWM shifts harmonic clusters to higher frequencies (around 2mf), improving power quality and simplifying filtering compared to Bipolar SPWM.
* **Modulation Indices (ma & mf):** Analysis of how altering the amplitude (ma) and frequency (mf) modulation indices affects fundamental output voltage, overmodulation distortion, and harmonic cluster distribution.
* **Load Dynamics:** Evaluation of inverter performance and current ripple reduction when shifting from purely resistive (R) to inductive (RL) loads.

## Prerequisites
* PSIM Simulation Software
