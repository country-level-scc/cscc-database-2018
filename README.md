Database of "Country-level social cost of carbon"

# Description

__run__: specifies the climate damages model ('bhm_lr': Burke, Hsiang & Miguel (2015) (BHM) long-run (5-lag) , pooled model;'bhm_richpoor_lr': BHM long-run, income-dependent (rich-poor) model; 'bhm_sr': BHM short-run (no lag), pooled model;'bhm_richpoor_sr': BHM short-run, income-dependent model; 'djo': Dell, Jones & Olken (2012) alternative impact function)

__dmgfuncpar__:	specifies whether full damage uncertainty is included in the simulation ('estimates': simulations use central damage parameters; 'bootstrap': damage function uncertainty is analyzed using bootstrapping)

__climate__: specifies whether full climate projection uncertainty is included in the simulation ('expected': simulations use central climate projection parameters; 'uncertain': climate uncertainty is analyzed using bootstrapping)

__SSP__: shared socioeconomic pathway -- socioeconomic projections including the country-level population and GDP projections

__RCP__: representative concentration pathway -- climate forcing scenario

__N__: number of generated runs 

__ISO3__: country code, for global values use 'WLD'	

__prtp__: pure rate of time preference, 'NA' for fixed discounting

__eta__: elasticity of marginal utility, 'NA' for fixed discounting

__dr__: fixed discount rate, 'NA' for endogenous/Ramsey-rule discounting cases	

__16.7%__: low (16.7% percentile) CSCC	

__50%__	: median CSCC

__83.3%__: high (83.3% percentile) CSCC

Note: The 3 statistics (low, median, high CSCC) are the median of the posterior distribution of the statistics after bayesian bootstrapping, i.e. for low, the median of the posterior distribution of the 16.7% percentile.

if you make use of this database, please cite: 
Ricke, K., L. Drouet, K. Caldeira and M. Tavoni. "Country-level social cost of carbon" (2018)

# CHANGELOG

v1 (26-16-2018)
* Version published with the paper

v2 (18-01-2019)
* Update Rich/Poor threshold: 2268.528$ for BHM, 2449.36$ for djo_richpoor.
* Use 5-lag DJO specification for DJO alternative specification.