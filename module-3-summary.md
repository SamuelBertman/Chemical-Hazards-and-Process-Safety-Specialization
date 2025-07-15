## Failure Calculations

- **Estimated failure rate over a year** (how measured) - defined as Mu = average failure rate.

- **Mu is the opposite of reliability**:  
    - 1 reliability = 0 Mu  
    - 0 reliability = 1 Mu

- **Failure density function importance**: 
  - If you take two points on the graph and calculate the area underneath between them, that will be the failure probability within a timeframe.

- **Mean Time Between Failures (MTBF)** 

- **Failure rate often forms a U-shaped graph**:  
  - At the start and end of a component’s life is when it is most likely to fail.

## Types of failure

- **Series failure**:  
  - If one of many components fails, the whole system fails.  
  - Failure probability mean can be calculated between them all.

- **Parallel failure**:  
  - If one of many components fails, the system continues to operate.  
  - The whole system fails only if all components fail.  
  - Reliability can be totalled between all components to calculate failure probability.

## Time (Tau) Definitions

- `Tau_r` = repair time period  
- `Tau_i` = inspection interval  
- `Tau_0` = operational time period  
- `Tau_U` = unnoticed period in which the failure goes undetected

## Event Tree Construction

1. Identify the initial event.
2. Lay out safety functions.
3. Define an upward arrow if the safety function is successful.
4. Define a downward arrow if the safety function fails.
5. Use the probability of failure to calculate the number of occurrences per year.
