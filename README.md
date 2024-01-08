# Overview
This repository is for depositing the data for a research article. It has the following branches:
- main
- result_rmsd1_noDIF
- result_rmsd1_withDIF
- result_rmsd2_noDIF
- result_rmsd2_withDIF

Below are details.

# Files in ``Main``
In ``main``, we have the following files about TIMSS math items:

	T19_G8_Item Parameters_Math.xlsx	item parameter file from TIMSS 2019
	T19_G8_ItemInfo_Math.xlsx		item information file from TIMSS 2019

They can also be downloaded at [TIMSS's website](https://timss2019.org/international-database/)

In addition, we have the following .RData files showing the simulated binary item responses:

	simulate_00values for settings.RData		 values of simulation settings
	simulate_NO.DIF_ngrp=2.RData		         simulated response data - no DIF, for two groups
	simulate_NO.DIF_ngrp=5.RData		         simulated response data - no DIF, for five groups
	simulate_NO.DIF_ngrp=10.RData		         simulated response data - no DIF, for ten groups
	simulate_NO.DIF_ngrp=15.RData		         simulated response data - no DIF, for 15 groups
	simulate_WITH.DIF_ngrp=2.RData		         simulated response data - with DIF, for two groups
	simulate_WITH.DIF_ngrp=5.RData		         simulated response data - with DIF, for five groups
	simulate_WITH.DIF_ngrp=10.RData		         simulated response data - with DIF, for ten groups
	simulate_WITH.DIF_ngrp=15.RData		         simulated response data - with DIF, for 15 groups

Note that we only cover ``ngrp = 2, 5, 10, and 15`` here (instead of ``ngrp = 2, 3, 4, ..., 15`` specified in the article) due to limited data storage space. 

# Files in ``result_rmsd1_noDIF``
In ``result_rmsd1_noDIF``, you can find .csv files about the calculated error rates of RMSD-1 in each simulated condition, when using DIF-free item response data (e.g., ``simulate_NO.DIF_ngrp=15.RData``).

# Files in ``result_rmsd1_withDIF``
In ``result_rmsd1_withDIF``, you can find .csv files about the calculated error rates of RMSD-1 in each simulated condition, when using DIF-contaminated item response data (e.g., ``simulate_WITH.DIF_ngrp=15.RData``).

# Files in ``result_rmsd2_noDIF``
In ``result_rmsd2_noDIF``, you can find .csv files about the calculated error rates of RMSD-2 in each simulated condition, when using DIF-free item response data (e.g., ``simulate_NO.DIF_ngrp=15.RData``).

# Files in ``result_rmsd2_withDIF``
In ``result_rmsd2_withDIF``, you can find .csv files about the calculated error rates of RMSD-2 in each simulated condition, when using DIF-contaminated item response data (e.g., ``simulate_WITH.DIF_ngrp=15.RData``).
