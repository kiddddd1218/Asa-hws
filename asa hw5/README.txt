There are five sections in this notebook: 
1. Basic setups: Initial condtions and rates. Plus a effect matrix.
2. Next Reaction: Simulations and plots using 'Next Reaction' algorithm. Answers both (a) and (c). 
3. Gillespie scheme: Simulations and plots using 'Gillespie scheme' algorithm. Answers both (a) and (c).
4. Tau-Leaping: Simulations and plots using 'Tau-Leaping' algorithm. Answers both (a) and (c).
5. Weak Order of Accuracy: Compare moments of tau-leaping and gillespie scheme at t = 1 and demonstrate the results in log-log plot. 

Dependency:
Python 3.x
Numpy
Matplotlib

Tips:
- Run Section 1 before running other sections. 
- If you want to run section 5, you need to run 1, 3, and 4 first. 
- If you wish to compare next reaction and tau-leaping in section 5, simply change simulate_Gill to simulate_reaction in section 5