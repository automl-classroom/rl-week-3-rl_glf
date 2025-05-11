# SARSA Tuning – Quick Summary

### 1. Did tuning help?

Yes! Default settings didn’t get rewards. After tuning (like alpha=0.2, gamma=0.74, epsilon=0.01), performance clearly improved.

---

### 2. What about the learning rate?

- Too high: unstable
- Too low: slow
- Around 0.2–0.4: best results

---

### 3. Best epsilon?

Small epsilons (0.01–0.05) worked best—mostly greedy with a bit of exploration. Too much or too little hurt performance.

---

### Final Note

Tuning really made SARSA learn faster and perform better. Worth it!