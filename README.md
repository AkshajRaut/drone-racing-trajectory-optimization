# Trajectory Optimization for Drone Racing

This project implements trajectory optimization methods for robot motion planning.  
The work focuses on generating smooth, feasible, and efficient trajectories by applying 
numerical optimization techniques, constraints handling, and cost-function design.

---

## 🚀 Features

- Formulation of trajectory optimization as a constrained minimization problem  
- Support for polynomial and discretized trajectory representations  
- Gradient-based optimization using iterative improvements  
- Handling of boundary conditions (start, goal, velocity constraints)  
- Cost terms for smoothness, energy, obstacle avoidance, and control effort  
- Visualization of optimized trajectories and convergence behavior  

---

## ▶️ Running the Notebook

Open the main notebook:

```
Programming_Assignment_2_Trajectory_Optimization_Akshaj.ipynb
```

You can execute cells sequentially to:

1. Define system dynamics and constraints  
2. Construct the trajectory parameterization  
3. Apply optimization loops  
4. Visualize trajectory improvements and final results  

---

## 📊 Outputs

- Optimized trajectory satisfying constraints  
- Cost reduction plots across iterations  
- Visual comparison between initial and optimized paths  
- Diagnostic data for gradients, constraints, and convergence  

---

## 📝 Reflection Summary

The notebook discusses:

- How initial guesses influence optimization stability  
- Trade‑offs between smoothness and dynamic feasibility  
- Why certain cost functions dominate optimization behavior  
- How constraints shape the feasible trajectory space  
