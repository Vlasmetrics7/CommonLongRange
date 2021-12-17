Common long-range dependence in a panel of hourly Nord Pool electricity prices and loads

In the zip file you have 7 main functions and 7 auxiliary functions.

Main functions:

- prices_memory 		Univariate and multivariate estimates of fractional integration orders of hourly
				electricity prices. First part of Table 2.

- loads_memory 			Univariate and multivariate estimates of fractional integration orders of hourly
				electricity loads. Second part of Table 2.

- factor_prices			Factor loadings and common factors of electricity prices. Figures 13 and 14.

- factor_loads			Factor loadings and common factors of electricity loads. Figures 15 and 16.

- gm_elecpurf2			Estimation of model in equation 5. (Table 3)

- gm_loadf2			Estimation of model in equation 6. (Table 4)

- panelsystem_elecloadvar1	Estimation of model in equation 7. (Table 5)


Auxiliary functions

- gdfm_onesided 		Estimates the Generalized Dynamic Factor Model  				
- spectral 			It is the spectral density decomposition used by all gdfm_onesided
- whittle			local Whittle
- extwhittle and extmghat	Extended local Whittle
- extmulti			Multivariate Extended local Whittle
- fracdiff 			Fractional differencing
- NeweyWest			Standard errors