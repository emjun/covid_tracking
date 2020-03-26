Data source: https://covidtracking.com/ \
High-level Hypothesis statement: "Higher positive test rate and/or low numbers of tests would imply a faster rate of growth later in the positive cases curve."

This hypothesis can be broken down into Hypothesis A and Hypothesis B, below.

**Hypothesis A:** "Higher positive test rate implies faster rate of growth later in the positive cases curve" 
- `hypo_a.ipynb`: Currently, Tea does not support modeling (working on providing this soon!),
  so I tested a simpler hypothesis: Higher positive test counts imply higher
  growth rate (as measured by increase in positive tests from yesterday, which is a metric reported in the data). 

*To be totally honest, I'm not sure this is a totally accurate operationalization of the original hypothesis, even without modeling capacity.*

**Hypothesis B:** "Low numbers of tests would imply a faster rate of growth later in the positive cases curve"
Tea program: hypo_b.ipynb


**Hypthesis C:** Higher testing rates is positively related to higher death count


Collaborators: Ben Zorn, Emery Berger