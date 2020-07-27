# stock-analysis

## Overview
The purpose of this analysis is to provide the client, Steve, an analysis of a dataset similar to one perviously provided (green_stocks). A more robust dataset has been analyzed, to include the entire stock market across 2017 and 2018 (VBA_Challenge). Specifically, information is provided to Steve on **total daily volume** and **yearly return** to best guide his clients' investments. 

## Results
When comparing all stocks in the most recent year, 2018, two stocks performed with a positive return: ENPH & RUN. When comparing stocks one year earlier, in 2017, 11 of the 12 stocks performed with a positive return: AY, CSIQ, DQ, ENPH, FSLR, HASI, JKS, RUN, SEDG, SPWR, VSLR. 
![2017Results](https://github.com/tarajarell/stock-analysis/blob/master/resources/2017%20Results.jpg)
![2018Results](https://github.com/tarajarell/stock-analysis/blob/master/resources/2018%20Results.jpg)

The time each analysis took was of importance to Steve, our client. Overall, the results of the VBA Analysis with all stocks considered ran faster than the DQ Analysis previously provided to him. Previously, 2017 analysis was 755.659 seconds and 2018 was 786.318 seconds. For this analysis, the run time was reduced to .154 seconds (2017) and .125 seconds (2018).

![2017Timer](https://github.com/tarajarell/stock-analysis/blob/master/resources/2017.jpg)
![2018Timer](https://github.com/tarajarell/stock-analysis/blob/master/resources/2018.jpg)

## Summary
The advantages of refactoring include making a code more efficient (in this case reducing run time) as well as 
