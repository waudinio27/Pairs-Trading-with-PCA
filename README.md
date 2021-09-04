# Pairs-Trading-with-PCA

This is my implementation of the Simple Pairs Trading Strategy from Dr. Thomas Starke from AAA Quants. 

https://github.com/rodler/quantinsti_statarb/blob/master/PCA_2.ipynb

Two pairs get downloaded with a choosen granularity from OANDA and are concated into a new pandas dataframe. 

The backtest is extended in a manner that allows to print out the actual position. Like this, it is possible to get an overview 
of the actual situation and allows to execute a pairs trading strategy by hand. 
Most importantly, it also shows when it is good to stay out of the market in times of choppy market regimes. 

Please keep in mind that today was the last trading day for DAX 30, because the main German index got extended with 10 more companies and will be called DAX 40 from the beginning of the next week. 

Hope you enjoy :-D 

And best regards
