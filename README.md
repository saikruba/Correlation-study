# Correlation Study: Spin and Orbital Periods in HMXBs

This project investigates correlations between the **spin period (Pₛ)**
of neutron stars and the **orbital period (P_b)** of their binary
systems in **High Mass X-ray Binaries (HMXBs)** within the Milky Way
Galaxy.

The analysis includes statistical correlation tests using:
- **Pearson coefficient**
- **Spearman coefficient**
- **Kendall's tau coefficient**

### Correlation Models

Two correlation models tested between the spin period ($P_s$) and orbital period ($P_b$), suggested by **Corbet**, can be written in the following form:

$$
P_s = k_1 P_b^{q_1}
$$

$$
P_s = k \big[(1 - e)^{3/2} P_b \big]^q
$$

where:  

- $P_s$ = spin period  
- $P_b$ = orbital period  
- $e$ = orbital eccentricity  
- $k, q, k_1, q_1$ = fit parameters  

---

**Typical parameter values:**  

- For X-ray pulsars with **Be companions**: $k_1 = 10,\; q_1 = 0.5$  
- For X-ray pulsars with **supergiant companions**: $k = 0.01,\; q = 2$  
- For X-ray pulsars with **massive companions**: (fits vary depending on dataset)  

---

**images/**
    Contains figures illustrating correlation coefficients and best-fit
    parameters.
    
 ![Correlation figure](correlation-study/images/corr_fig1.png)



**poster.pdf**
    A summary poster of the analysis, including detailed results and
    tables.
