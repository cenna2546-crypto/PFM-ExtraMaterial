# PFM-ExtraMaterial

Anonymous repository meant to give access to figures not easily accessible on Open Review for Product Flow Matching (PFM).

 **(1) Quantitative experiment for commutativity of PFM using FID, comparison with CFM:**
 
<p align="center">
  <img src="Q_CelebA.png" alt="My Figure" width="800"/>
</p>

Same results in a table: 

<div align="center">
  
| Method | Path 1: t→s | Path 2: s→t | Path 3: Diagonal |
|--------|-------------|-------------|------------------|
| PFM    | 3.0832 ± 0.3006 | 2.4917 ± 0.2186 |2.2869 ± 0.2156|                 -
| CFM   |0.1025 ± 0.0065|0.1477 ± 0.0199|0.1274 ± 0.0125|

</div>

**(2) Further empirical evidence for relation between PFM and Wasserstein Barycenters**

Table A. Wasserstein Distance between $\rho_{t,s}^{PFM}$ and Free Support Wassertein Barycenter Estimation:

<div align="center">
 
|s/t| 0.000 | 0.100 | 0.325 | 0.550 | 0.775 | 1.000 |
|---|-------|-------|-------|-------|-------|-------|
| 0.000 | 0.00000 | 0.001175 | 0.007174 | 0.007247 | 0.011600 | 0.010786 |
| 0.100 | 0.001557 |0.002298 |0.007938 |0.008053 | 0.012207 | 0.011384 |
|0.325 | 0.006204 | 0.006678 |0.010929 |0.010407 |0.014029 |0.012580|
| 0.550 |0.008765 | 0.009403 |0.012985 |0.012631 |0.015574 |0.014951|
| 0.775 |0.011151 |0.011616 |0.014526 |0.013562 |0.016022 |0.016893|
|1.000 |0.014151 |0.014509 |0.016650 |0.015850 | 0.020622 |0.022103|

</div>

Table B. Wasserstein Distance between source (circle) and targets (triangle and rotated triangle) in figure 2 of the paper:

<div align="center">
 
|  | Source | Target 1 | Target 2 |
|--------|-------------|-------------|------------------|
Source | 0.000000 | 1.009144 | 1.001163 |
| Target 1 | 1.009144 | 0.000000 |1.412536 |
| Target 2 |1.001163 | 1.412536 |0.000000 |

</div>













