Binomial Operating Characteristic Curves
========================================================
This web application calculates and plots operating characterstic curves for up to four tests. 

Input Parameters
----------------
Input parameters for the app include:  

1. Number of shots for each test  
2. Number of failures for each test

By default all four tests are plotted. One can modify the number of tests plotted by unselecting checkbox
next to the test entry values. 

Modifying Plot Attributes
-------------------------

To modify plot attributes just check the checkbox next to the "Modify Plot Attributes" on the left side panel.   
This allows the user to customize the plot such as changing the plot title, axes titles, test names, text sizes, thickness of lines, and other functionalities. 

Downloads
---------

The user can download the full dataset generated and plotted by the app by clicking on the "Download Data Sample" botton 
on the lower left side of the page.  

To download the plot in PDF or PNG formats just click the corresponding botton on the lower left side of the page. 


More Resources:
---------------

1. [Operating Characterstic Curve plotting calculator](http://spark.rstudio.com/statstudio/OC5/). Similar to this app but for continuous response data.  
2. [Mean Time Between Failure calculator with confidence intervals](http://spark.rstudio.com/statstudio/MTBF/)  
3. [Mean Time Between Failure required test time calculator](http://spark.rstudio.com/statstudio/MTBFTestTime/)


$$
\begin{aligned}
\dot{x} & = \sigma(y-x) \\
\int x \, dx& = \frac{x^2}{2} + C
\end{aligned}
$$
