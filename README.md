# Marine-gastropod-Phorcus-turbinatus-persistently-avoids-cliff-areas-impacted-by-artificial-light-
Data and R code from the research "Marine gastropod Phorcus turbinatus persistently avoids cliff areas impacted by artificial light at night (ALAN)"

This repository contains the complete dataset and R code used to reproduce the statistical analyses and figures reported in the study, “Marine gastropod Phorcus turbinatus persistently avoids cliff areas impacted by artificial light at night (ALAN).”
Filippo Chisci1,2, Cristiano Bertolucci3,4, Paolo Lazzari5, Elena Maggi6
1. Department of Biology, University of Florence, Florence, Italy 
2. National Institute of Oceanography and Applied Geophysics - OGS, Leghorn, Italy
3. Department of Life Sciences and Biotechnology, University of Ferrara, Ferrara, Italy
4 Biology and Evolution of Marine Organisms, Stazione Zoologica Anton Dohrn, Naples, Italy
5. Department of Oceanography, National Institute of Oceanography and Applied Geophysics- OGS
Trieste, Italy
6. Department of Biology, CoNISMa, University of Pisa, Pisa, Italy

The repository contains a single R script and three datasets in both xls and csv format:

Phorcusturbinatus.xls contains the data required for all analyses of P. turbinatus density in control areas and areas impacted by ALAN.
Data indicate day and time of start sampling, Time indicate 1 of the 4 observation time in the experiment, Zone indicate 1 of the 4 site of the sampling, LITUNLIT indicate if the site was impacted by ALAN, Boulder is the ID of the boulder sampled,Side indicate if the plot sampled was in the lanward or seaward side, spatial_replication is the ID of the plot (AB, CD, EF, GH indicate a complete plot, A,B,C,D,E,F,G,H indicate only an half of corresponding plot, UW indicate the number of individuals under the water level, WL indicate the number of individual at the water level, OW indicate indicate the number of individuals over the water level, Sheltered is the number of individual hide behind a repair, Nosheltered is the number of individuals outside the repair, TOT is the sum of individuals OW and UW , Nrep is an ID for indicate plot not used in analysis, MOON indicate if in the day of the sampling there was new or full moon, Day indicate the corresponding number of the day in the year, Temp is the temperature during the sampling, Tmax is the maximum temperature reach in a specifical day of sampling
Position.xls contains the position of all individuals observed in each plot.

Data indicate day and time of start sampling, Time indicate 1 of the 4 observation time in the experiment, Zone indicate 1 of the 4 site of the sampling, LITUNLIT indicate if the site was impacted by ALAN, Boulder is the ID of the boulder sampled ,Side indicate if the plot sampled was in the lanward or seaward side, spatial_replication is the ID of the plot (AB, CD, EF, GH),Individuo is the ID of every individuals observed, Level is the ID of the rectangle which the individuals are observed,MOON indicate if in the day of the sampling there was new or full moon, Position indicate if the individuals were observed over or under the water level

Verticalmovement.xlsx contains data on the vertical movement of individuals between the Lights_on and Night observation phases. Value indicate the movement occurs between the two observation, Side indicate  if the individual obaerved was in the lanward or seaward side, Light indicate if the individuals were observed in an area impacted by ALAN, Moon  indicate if in the day of the sampling there was new or full moon,
