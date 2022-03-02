# Pairs-Trading-with-PCA

This is my implementation of the Simple Pairs Trading Strategy from Dr. Thomas Starke from AAA Quants.

https://github.com/rodler/quantinsti_statarb/blob/master/PCA_2.ipynb

Two pairs get downloaded with a chosen granularity from OANDA and are concated into a new pandas dataframe.

The backtest is extended in a manner that allows you to print out the current position. Like this, it is possible to get an overview of the current situation and you can execute a pairs trading strategy by hand. Most importantly, it also shows when it is good to stay out of the market in times of choppy market regimes.

Hope you enjoy it :-D

And best regards
