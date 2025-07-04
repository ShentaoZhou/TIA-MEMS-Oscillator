# TIA-MEMS-Oscillator
belong to neu-ucb tvip
Use a piezoelectric MEMS as a frequency filter and a TIA to compensate the Motion Resistabnce of the MEMS to make the closed-loop system oscillate to generate a clock signal.
![屏幕截图 2025-06-26 220926](https://github.com/user-attachments/assets/c3d14d07-0151-4823-bb10-b8540fdbc658)
To let the oscillator start up, we need to satisfy Barkhausen Criterion:

The Barkhausen criterion for oscillator startup consists of two conditions:

1. **Loop Gain Condition**  
   The magnitude of the loop gain at the resonant frequency must satisfy:  
   `|A_loop(jω₀)| ≥ 1`

2. **Loop Phase Condition**  
   The total phase shift around the feedback loop at the same frequency must be an integer multiple of 360°:  
   `∠A_loop(jω₀) = 0° (mod 360°)`

