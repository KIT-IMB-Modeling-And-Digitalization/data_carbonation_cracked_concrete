# Dataset of the Article "Comparative analysis of engineering carbonation model extensions to account for pre-existing cracks"

The database `database_carbonation_cracked_concrete.CSV` contains data used to evaluate different carbonation models for cracked concrete in the article [Comparative analysis of engineering carbonation model extensions to account for pre-existing crack]().

The literature data was collected from various articles partially using a [PlotDigitizer](https://automeris.io/WebPlotDigitizer/).
In this repository the database is reported as:

| Category           | Description|
|----------------|--------------|
| Ref            |   reference ID |
| Mix type       | concrete/ mortar/ paste |
| binder type    | OPC / Fa+OPC |
| crack type     | notch / natural /no crack |
| w/b [-]        | water-binder ratio |
| exposure time [year] | exposure time to $CO_2$ |
| crack width [mm] | crack width at the surface |
| crack depth [mm] | crack depth |
| carbonation depth [mm] | Measured carbonation depth. For crack width=0 and crack depth=0 it is the carbonation depth of the uncreacked conecrete. Otherwise it is the maximum carbonation depth at the location of a crack. |
| CO2 [%]        | $CO_2$ concentration of the experiment |
| RH [%]         | relative humidity of the experiment |
| DOI            | DOI link |


The data in this database is from the following publications:

| Ref | Publication | 
|---|----|
| Guo.2022| Guo, Q. et al. (2022) [Analysis of Carbonation Behavior of Cracked Concrete](https://doi.org/10.3390/ma15134518) in: Materials (Basel, Switzerland) 15, Nr. 13, p. 4518. | 
|Schutter.1999|de Schutter, G. [Quantification of the influence of cracks in concrete structures on carbonation and chloride penetration](https://doi.org/10.1680/macr.1999.51.6.427). Magazine of Concrete Research 1999, 51, 427–435. |
|Mullem.2020|van Mullem, T.; de Meyst, L.; Handoyo, J.P.; Caspeele, R.; de Belie, N.; van den Heede, P. [Influence of Crack Geometry and Crack Width on Carbonation of High-Volume Fly Ash (HVFA) Mortar](https://doi.org/https://doi.org/10.1007/978-3-030-76551-4_6). In Proceedings of the 3rd RILEM Spring Convention and Conference 542 (RSCC 2020); 2020; Vol. RILEM Bookseries 33, pp. 59–67.|
|Zhang.2011|Zhang, S.P.; Zong, L.; Dong, L.F.; Zhang, W. [Influence of Cracking on Carbonation of Cement-Based Materials](https://doi.org/10.4028/www.scientific.net/AMR.261-263.84). Advanced Materials Research 2011, 261-263, 84–88.    |

New data from experiments of this article:

| file | reference | 
|---|----|
|Schultheiss.2023|Schultheiß, A.L.; Patel, R.A; Vogel M.; Dehn, F. [Comparative analysis of engineering carbonation model extensions to account for pre-existing cracks](), |



Furthemore, the input parameter and prediction results of the four models compared in [Comparative analysis of engineering carbonation model extensions to account for pre-existing cracks]() are given in the file `prediction_results.csv`.
| Category                 | Description                            |
|--------------------------|-----------------------------------|
| Ref                      |   reference ID |
| binder type              |   OPC / Fa+OPC                                |
| w/b                      |   water-binder ratio                                |
| R_acc^-1 [(mm^2/year)/(kgCO2/m^3)) |   inverse carbonation resistance parameter calculated with the $CO_2$ concentration of the experiment and the carbonation depth $x_c,uncr (t)$ determined for $t$ closest to 28 days $CO_2$ exposure.                       |
| RH [%]                   |   relative humidity of the experiment                                |
| t_c [days]               |   curing time befoe exposure                                |
| ToW [-]                  |   time of wettness                                |
| p_SR [-]                 |   probability of driving rain                                |
| C_s [kgCO_2/m^3]         |   $CO_2$ concentration                                |
| C [kg/m^3]               |   cement content                              |
| CaO [-]                  |   calciumoxide content in cement                                 |
| alpha [-]                |   degree of hydration                                |
| exposure time [year]     |   exposure time to $CO_2$                                |
| crack width [mm]         |   crack width at the surface                                |
| crack depth [mm]          |   crack depth                                |
| carbonation depth [mm]   |  Measured carbonation depth. For crack width=0 and crack depth=0 it is the carbonation depth of the uncreacked conecrete. Otherwise it is the maximum carbonation depth at the location of a crack.                                 |
| CIF(w) [mm]              |   Predicted carbonation depth with the CIF(w) approach for cracked concrete                                |
| CIF(w;d) [mm]            |   Predicted carbonation depth with the CIF(w, d) approach for cracked concrete                                  |
| diffusion-based [mm]     |   Predicted carbonation depth with the diffusion-based approach for cracked concrete                                  |
| crack depth adaption [mm]|   Predicted carbonation depth with the crack depth adaption  for cracked concrete                                  |
| fib carbonation model [mm]|  Predicted carbonation depth with the fib carbonation model for uncracked concrete                                 |





To use the provided datasets please cite:

Schultheiß, A.L.; Patel, R.A.; Vogel, M.; Dehn, F. [Comparative Analysis of Engineering Carbonation Model Extensions to Account for Pre-Existing Cracks](https://doi.org/10.3390/ma16186177). Materials 2023, 16, 6177. https://doi.org/10.3390/ma16186177
