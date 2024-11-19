# Queueing System Simulation

## Overview
This project simulates a single-server queueing system representing a router with one incoming link. The simulation studies system performance under various conditions.

## System Description

### Arrival Process
- Packets arrive following a Poisson process
- Interarrival times are exponentially distributed
- Probability density function: a(t) = λe^(-λt), t ≥ 0
- Mean interarrival time: 1/λ
- λ represents arrival rate (packets/sec)

### Service Process
- Service times are exponentially distributed
- Probability density function: b(t) = μe^(-μt), t ≥ 0
- Mean service time: 1/μ
- μ represents service rate (packets/sec)

### Queue Characteristics
- Single server (CPU)
- Infinite queue capacity
- First-Come-First-Served (FCFS) discipline
- Packets exit system after processing

## Implementation Requirements

### Input Parameters
- λ (arrival rate)
- μ (service rate)
- Simulation duration

### Output Metrics
- Average queue length
- Average waiting time
- Server utilization
- Throughput

### Validation
Simulation results should be compared with theoretical values from M/M/1 queueing theory.

## Due Date
January 19, 2022

## Project Goals
1. Understand queueing system behavior through simulation
2. Analyze system performance under various loads
3. Gain practical experience with discrete event simulation
4. Compare simulation results with analytical solutions