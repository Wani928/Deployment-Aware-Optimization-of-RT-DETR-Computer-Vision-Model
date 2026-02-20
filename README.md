# Deployment-Aware Optimization of RT-DETR

Systematic analysis of the trade-off between detection accuracy, inference latency, and power consumption in Real-Time Detection Transformers (RT-DETR).

This project investigates how the number of object queries (*k*) influences:

- Mean Average Precision (mAP)
- Inference time
- Energy consumption

The work focuses on deployment-aware tuning for resource-constrained and edge platforms.

---

## Motivation

Transformer-based object detectors introduce architectural parameters that directly affect computational cost.  

However, these trade-offs are rarely quantified from a real-world deployment perspective.

This project conducts a structured experimental sweep over query values and applies multi-objective optimization to identify optimal operating points under:

- Accuracy constraints  
- Latency constraints  
- Power constraints  

---

## Key Contributions

- Systematic empirical evaluation across discrete query values  
- Separate encoder/decoder performance analysis  
- Pareto-based multi-objective optimization  
- Constrained and unconstrained operating point selection  
- Demonstration of computational savings without accuracy loss   

---

## Publication Status

The work is currently under internal discussion for potential publication.

To preserve academic integrity, the full experimental implementation and model modifications are not publicly available at this time.

Further updates will be provided if publication proceeds.

---

## 👤 Author

Wanangwa Nyasulu  
Zhuoron Dong 
Ahmed Badr

M2 Mobile and Autonomous Robotic Systems (MARS)  
Grenoble INP – Ense3
