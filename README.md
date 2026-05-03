# AGV Flow-Shop Scheduling

Compute near-optimal schedules for flow-shop systems with a single AGV transport constraint.

## Problem
- $n$ identical jobs, $m$ sequential stations  
- Processing time $p_i$ per station  
- One AGV, one job at a time, no intermediate storage  
- Objective: minimize makespan  

## Approach
- Analyze a simple sequential transport schedule (near-optimal in key regimes)  
- Exact constant-time solution for 2 stations  
- Generalize via cycle-based schedule structure for arbitrary $m$  
- Characterize a class of optimal schedules  

## Result
- $(1+\varepsilon)$-approximation for any $\varepsilon > 0$  
- Scales independently of number of jobs  

## Why it matters
- Fast, provable scheduling for constrained robotic transport  
- Applicable to automated warehouses and manufacturing lines  

## Status
- Theoretical results + constructive algorithms  
