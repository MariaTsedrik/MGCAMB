MGCAMB 
===========
forked from https://github.com/sfu-cosmo/MGCAMB_v4

## Linder Gamma 
 
- To run MGCAMB for the time-independent no-slip ($\gamma=1$) growth index parametrisation specify

```bash
MG_flag = 2
alt_MG_flag = 1
Linder_gamma = 0.4
```

- To run MGCAMB for the time-dependent ($\gamma_{\rm Linder}=\gamma_0+\gamma_1\frac{z^2}{1+z}$) no-slip ($\gamma=1$) growth index parametrisation specify

```bash
MG_flag = 2
alt_MG_flag = 2
Linder_gamma_0 = 0.4
Linder_gamma_1 = 0.1
```

- To run MGCAMB for the time-independent growth index parametrisation with $\Sigma=\frac{\mu(1+\gamma)}{2}=1$ specify

```bash
MG_flag = 2
alt_MG_flag = 3
Linder_gamma = 0.4
```