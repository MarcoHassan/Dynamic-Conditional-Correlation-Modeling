# Dynamic Conditional Correlation Model

Author: Marco Hassan & Martina Porubcova & Mattia Palese

Class: Financial Volatility

Literature: This study is a reproduction of the paper "Financialization in commodity markets: A passing trend or the new normal?" of Zeno Adams and Thorsten Glück published in 2015 by Elsevier.

# The idea

The idea is to check at the trend of the correlation between the main equity market and the commodity indices after the financial crises.

The thesis is that after such a crises commodities bacame an investment asset and consequently shifted the times series correlation between the series shifting moreover the commodity prices from the underlying real economic activity.

A simple plot of the S&P 500 in red vs. the GSCI composite index seems to confirm that.

![image](https://user-images.githubusercontent.com/42472072/52442984-30936700-2b2d-11e9-8e33-9679d93cc6a4.png)

Important is nonetheless to notice that correlation, like volatility is a non observed value but rather a statistics computed at determined time points given a sufficient number of observations.

Given that we are interested in a times series development of correlation a more advanced techique is necessary. To extract the times series behaviour of commodities and equity indices we therefore decided upon approximating the correlation observations at each time point in the series by using the covariates estimation that results applying a multivarite GARCH model to the series. 

Mild evidence is found for such behaviour especially in the Alluminium and Copper series.

![image](https://user-images.githubusercontent.com/42472072/52443598-ce3b6600-2b2e-11e9-8a0a-f65ce30e39ae.png)
