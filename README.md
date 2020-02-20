# R Package 'MSwM'

#### !! - Important Disclaimer - !!

This package is a slightly modified version of the officially released ```MSwM``` package, 
which I modified for my own specific purposes. 
This fork has not been tested outside the limited scope of my code and machine. 
Feel free to use at your own risk.

The main modification is that now the ```plotProb``` function (with parameter 
```which > 1```) also includes labels for the x axis of the main time series 
plot of the dependent variable. This is particularly useful when time 
series object are fed to ```MSwM``` with named rows. Every data is turned into 
a dataframe but ts keep their dates as row names, which are kept in the 
```MSwM``` model object and recycled to label the x-axis.
