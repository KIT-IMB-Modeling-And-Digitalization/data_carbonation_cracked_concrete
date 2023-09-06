# Dataset of the Article "Comparative analysis of engineering carbonation model extensions to account for pre-existing cracks"

The database `database_carbonation_cracked_concrete.CSV` contains data used to evaluate different carbonation models for cracked concrete in the article [Comparative analysis of engineering carbonation model extensions to account for pre-existing crack]().

In this repository the database is reported as:

|Ref|Mix type|binder type|crack type|w/b [-]|exposure time [year]|crack width [mm]|	crack depth [mm]|carbonation depth [mm]|CO2 [%]|RH [%]|DOI|
|---|----|---|---|----|---|---|----|---|---|----|---|
|Reference ID|concrete/ mortar/ paste|OPC / Fa+OPC|notch / natural|water-binder ratio|exposure time to $CO_2$|crack width at the surface|crack depth|Measured carbonation depth. For crack width=0 and crack depth=0 it is the carbonation depth of the uncreacked conecrete. Otherwise it is the maximum carbonation depth at the location of a crack.|$CO_2$ concentration of the experiment|relative humidity of the experiment|DOI link|


The literature data was collected from various articles partially using a [PlotDigitizer](https://automeris.io/WebPlotDigitizer/).
The references for the literature data are listed blow:


Furthemore, the prediction results of the four models are given in the file `prediction_results.csv`.
|Ref|binder type|w/b|exposure time [years]|crack_width|crack_depth|Measured carbonation depth|CIF(w)|CIF(w,d)|diffusion-based|crack depth adaption|fib carbonation model|
|---|----|---|---|----|---|---|----|---|---|----|---|
|Reference ID|OPC / Fa+OPC|water-binder ratio|exposure time to $CO_2$|crack width at the surface|crack depth|Measured carbonation depth. For crack width=0 and crack depth=0 it is the carbonation depth of the uncreacked conecrete. Otherwise it is the maximum carbonation depth at the location of a crack.|Carbonation depth [mm] calculated with the CIF(w) model|Carbonation depth [mm] calculated with the CIF (w,d) model|Carbonation depth [mm] calculated with the diffusion based model|Carbonation depth [mm] calculated with the crack depth adaption|Carbonation depth [mm] calculated with the fib carbonation model|


| Ref | reference | 
|---|----|
| Guo.2022| Guo, Q. et al. (2022) [Analysis of Carbonation Behavior of Cracked Concrete](https://doi.org/10.3390/ma15134518) in: Materials (Basel, Switzerland) 15, Nr. 13, p. 4518. | 
|Schutter.1999|de Schutter, G. [Quantification of the influence of cracks in concrete structures on carbonation and chloride penetration](https://doi.org/10.1680/macr.1999.51.6.427). Magazine of Concrete Research 1999, 51, 427–435. |
|Mullem.2020|van Mullem, T.; de Meyst, L.; Handoyo, J.P.; Caspeele, R.; de Belie, N.; van den Heede, P. [Influence of Crack Geometry and Crack Width on Carbonation of High-Volume Fly Ash (HVFA) Mortar](https://doi.org/https://doi.org/10.1007/978-3-030-76551-4_6). In Proceedings of the 3rd RILEM Spring Convention and Conference 542 (RSCC 2020); 2020; Vol. RILEM Bookseries 33, pp. 59–67.|
|Zhang.2011|Zhang, S.P.; Zong, L.; Dong, L.F.; Zhang, W. [Influence of Cracking on Carbonation of Cement-Based Materials](https://doi.org/10.4028/www.scientific.net/AMR.261-263.84). Advanced Materials Research 2011, 261-263, 84–88.    |

New data from experiments of this article:

| file | reference | 
|---|----|
|Schultheiss.2023|Schultheiß, A.L.; Patel, R.A; Vogel M.; Dehn, F. [Comparative analysis of engineering carbonation model extensions to account for pre-existing cracks](), |


To use the provided dataset please cite:

Schultheiß, A.L.; Patel, R.A; Vogel M.; Dehn, F. [Comparative analysis of engineering carbonation model extensions to account for pre-existing cracks](),
