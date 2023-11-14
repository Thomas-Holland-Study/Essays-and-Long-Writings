---
title: 'IB PMS Practical Week 5: ‘‘Find that Phenotype II"'
author: "BGN: 54"
tags:
  - lab_report
---

# Photosynthetic Gas Exchange (Licor) - RbcS mutants

## Hypotheses
> *How do you expect the assimilation (A) and evaporation (E) rates to vary between wt and ssu2? Why?*

It is expected that there will be a decrease in both the assimilation and evaporation levels of the plant in the ssu2 mutant. This is due to the decrease in the levels of $\ce{CO_{2}}$ due to decreased levels of [[RuBisCo]] activity. 

> *How do you expect water use efficiency (WUE) to vary between wt and ssu2? Why?*

We expect the water use efficiency in the mutant to decrease due to the reduced carbon assimilated per unit of water. 

> *What variation do you expect to measure in stomatal conductance $g_{s}$ and internal $\ce{[CO2]}$, $c_{i}$ between wt and ssu2? Why?*

I would expect no difference between the mutant and wild type as this would be an indirect effect in which multiple factors would affect the gas flow. For example, the stomata might be open due to the signalling of assimilation deficiencies and thus an increased level of stomatal conductance and an increased internal carbon dioxide concentration. However, this increase in internal carbon dioxide levels might lead to the closing of the stomata as the guard cells would sense the higher levels of internal carbon dioxide due to the lack of assimilation. 

> *From the A/ci responses, how do you expect $V_{cmax}$ and $R_{d}$ to vary between wt and ssu2? Why?*

$V_{cmax}$: we expect a decrease in the rubisco quantity in the mutant, and so the efficiency of fixing will decrease. Thus $V_{cmax}$ will decrease. 
$C_{i}$: we expect less respiration to take place in the mutant as a function of less carbon fixation, decreasing the levels of glucose available for respiration as well as a signalling response to decrease the levels of respiration in the aim of preserving the plant's carbon stores. 

## Description of results

- From the A/Ci fitted model, we can see that there is a decrease in the carbon dioxide assimilation levels at each internal carbon dioxide concentration level in the ssu2 mutant when compared to the wild type ($F_{df=3,8} = 3024, p<0.0001$). This supports the hypothesis made.
	- The diagnostic plots look okay; just a slight concern could be raised around the residuals vs leverage where points 6 and 12 have quite high leverage on the model. 
- From the intercellular CO2 concentrations (Ci), we can see that the ssu2 had an increase in Ci with an average of 375.17 umol CO2/mol compared to the wild type, where the Ci was at 285.33 umol CO2/mol ($F_{df=1,10} = 50.668, p<0.0001$). This does not support our hypothesis.
	- The diagnostic plots show that the data is not homogeneously spread around the mean fitted values between the ssu2 and wt. However, there is no cause for significant concern about this. 
- From the stomatal conductance to water vapour, there appears to be no significant correlation between the water conductance and the ssu2 gene ($F_{df=1,10} = 0.1098, p>0.7$).
	- The diagnostic plots raise no concern. 
- From the CO2 assimilation data, we can see that there is a large increase in the assimilation of carbon dioxide in wt compared to ssu2 with an average of 12.7 umol CO2/m2/s and 3.09 umol CO2/m2/s, respectively ($F_{df=1,10} = 153.47, p<0.0001$).
	-  The diagnostic plots show that the data is not homogeneously spread around the mean fitted values between the ssu2 and wt. However, there is no cause for significant concern about this. 
- From the transpiration data there is no difference in the transpiration levels between the ssu2 mutant and the wildtype ($F_{df=1,10} = 0.5079, p>0.45$).
	- The diagnostic plots raise no concern.
- From the intrinsic water use efficiency data the wildtype has a large increase in water use efficiency with over three times the efficiency compared to the ssu2 mutant ($F_{df=1,10} = 33.614, p<0.001$).
	- There are slightly higher residuals for the wildtype dataset; however, this is no direct cause of concern as the more extreme residuals are along the 1:1 on the normalQ-Q plot. 

# Light use - RbcS Mutants (PAM fluorometer and Chlorophyll meter)

## Hypothesis

> *How do you expect chlorophyll content to vary between wt and ssu2? Why?*

We expect a decrease in the chlorophyll content in the mutant as a feedback mechanism to prevent the waste of the plant's resources. 

> *How do you expect maximal $\Phi PSII$ (Fv/Fm) to vary between wt and ssu2? Why?*

We do not expect the maximal $\Phi PSII$ to change, as this is independent of RuBisCo and its activity. 

> *Do you expect to find a difference in ETR between wt and ssu2? Why?*

We expect the ETR to decrease in ssu2 due to a slower return of the proton receptors (NAD and FAD), which would lead to a backing up of the electron transport chains in photosynthesis. 

> Do you expect to find a difference in NPQ between wt and ssu2? Why?

We expect a decrease in the levels of NPQ in ssu2 and, thus an increase in fluorescence to counter the reduction in NPQ ($NPQ+Flur.+PC=1$, and if PC is constant and $NPQ\downarrow \implies Flur. \uparrow$). This occurs when there is not enough light to trigger photochemistry. 
## Description of results
- The relative chlorophyll content is higher in the wildtype compared to the ssu2 mutant by just over 50% ($F_{df=1,10} = 226.26, p<0.0001$).
	-  The diagnostic plots show that the data is not homogeneously spread around the mean fitted values between the ssu2 and wt. However, there is no cause for significant concern about this. 
- There is a increase of about 2x of the electron transport rate in the wild type when compared to the ssu2 mutant ($F_{df=1,10} = 22.922, p<0.001$).
	-  The diagnostic plots show no cause for concern over the data. 
- There appears to be no difference in the maximal PSII quantum efficiency between the wildtype and ssu2 mutant ($F_{df=1,10} = 1.3235, p>0.25$).
	- The diagnostic plots show that the data does not follow the 1:1 line on the normalQ-Q plot, suggesting that there might be a better model if a transformation was performed on the data. 
- There appears to be an outlier with one of the wildtype data points; however, the data suggests that there is no relationship between the wildtype and the ssu2 mutant and the NPQ amounts. It might be worth collecting more data on this and confirming the outlier. 
- The PSII operating efficiency is over double in the wildtype when compared with the ssu2 mutant ($F_{df=1,10} = 22.922, p<0.001$).
	- The diagnostic plots show no cause for concern. 
# Light harvesting - PsbS Mutant (chlorophyll fluorescence imager)
## Hypothesis

> *Which genotype would you expect to have the highest NPQ? Why?*

We would expect the highest levels of NPQ in the over-expressor of PsbS. This is due to PsbS being a key protein in the regulation and action of NPQ. 

> *Do you expect to find differences in maximal $\Phi PSII$ (Fv/Fm) between these three genotypes? Why?*

We expect the maximal efficiency of PSII to be the same as all of the reaction sites are open at the start of the reaction there is no NPQ due to the speed of the flash.
## Description of results

- The PSII quantum efficiency data shows no significant difference between the groups ($F_{df=2,15} = 2.284, p>0.10$); however, from the data, we could argue that there are three groups of different levels of efficiency, which would match up with the three types of genotype.
	- The diagnostic plots show no cause for concern, although the normalQ-Q plot is off slightly. 
- There is a large difference in the NPQ between the three genotypes, with there being almost minimal NPQ in genotype B (0.38), 2.94 in C and almost 50% more in genotype A ($F_{df=2,15} = 320.3, p<0.00001$).
	- The residual plots show no cause for concern.
# Physiological interpretation

The photosynthetic gas exchange results indicate a significant decrease in carbon dioxide assimilation levels in the ssu2 mutant compared to the wild type, supporting the hypothesis of reduced RuBisCo activity in the mutant. Contrary to expectations, intercellular CO2 concentrations (Ci) increased in the ssu2 mutant, suggesting complex interactions in response to assimilation deficiencies. Stomatal conductance and transpiration showed no significant differences between the mutant and wild type. However, water use efficiency (WUE) decreased in the mutant, aligning with the reduced carbon assimilation per unit of water. From the A/Ci responses, both $V_{cmax}$ and $R_{d}$ were expected to decrease in the mutant due to decreased Rubisco quantity and reduced respiration, supporting the observed decrease in carbon fixation efficiency.

In the light use experiment, chlorophyll content was significantly lower in the ssu2 mutant, indicating a potential feedback mechanism to conserve resources. Electron transport rate (ETR) decreased in the mutant, possibly due to slower proton receptor return, causing electron transport chain backup. Maximal $\Phi PSII$ and NPQ exhibited no significant differences, suggesting independence from RuBisCo activity.

For the light harvesting experiment, the PsbS mutant exhibited varying levels of PSII quantum efficiency, indicating potential differences in genotype responses. The NPQ levels differed significantly between genotypes, with the over-expressor (genotype A) showing the highest NPQ, aligning with the hypothesis that PsbS overexpression leads to increased non-photochemical quenching.

In summary, the physiological interpretation suggests that the ssu2 mutant experiences compromised photosynthetic performance with reduced carbon assimilation and altered gas exchange parameters. The light use and harvesting experiments reveal complex interactions between genotype and photosynthetic parameters, highlighting the intricate regulatory mechanisms governing plant responses to genetic modifications.