# Portfolio-optimization-using-Monte-Carlo-simulation

## Introduction

This project discusses implementation of Monte Carlo Simulations for portfolio
optimization and asset allocation. To be more specific, this technique aims to construct
many random portfolios of equities in order to find three specific popular portfolio types:
minimum risk, maximum return, and maximum Sharpe Ratio.

## Monte Carlo simulation

Monte Carlo simulation is a computational technique that utilizes random sampling and
statistical analysis to model and evaluate complex systems or processes. By generating
numerous iterations of possible outcomes, it provides insights into the range of potential
results and helps make informed decisions under uncertainty


## Instruction
(1) Access to the ipynb file (or html file just to watch, not perform any programming)
consists of the Python code to generate simulations based on past stocks data.
Then, we install the needed library in the part library installation.



(1) Gather the needed stock by filling the stock name and time (start and end).


(2) Perform past data description using some tools such as line graph, boxplot, or
scatter plot to see some notable characteristic of the stocks. This part is optional.


(3) Prepare for the simulations by calculating the annual returns and covariance
matrix, enter the number of simulations/portfolios/weights


(4) Now we do the simulations in two loops (the explanation of the code can be
found in the file)


(5) The simulation returns the result in sim_port. Now we can do analysis and make
decisions by visualizing the simulations using seaborn (to draw distributions) or
scatter plot (to compare the advantages and disadvantages and decide your
desired outcome)

## Reference :

https://github.com/LucS12/MonteCarlo-assetAllocation

Detemple, J. B., Garcia,s R., & Rindisbacher, M. (2003). A Monte Carlo Method for
Optimal Portfolios. The Journal of Finance, 58(1), 401–446.

http://www.jstor.org/stable/3094492.

K. Eisenhardt, Building Theories from Case-Study Research, Academy of Management
Review 14/4 (1989)116–121.

I.T. Nemuth, Practical Use of Monte Carlo Simulation for Risk Management within the
International Construction Industry, In Grauber, Schmidt & Proske: Proceedings of the
6th International Probabilistic Workshop, Darmstadt, 2008.

Towardsdatascience,
https://towardsdatascience.com/optimization-with-python-how-to-make-the-most-amount
-of-money-with-the-least-amount-of-risk-1ebebf5b2f29

B. Postace, Wordpress,
https://insightr.wordpress.com/2017/08/27/pricing-optimization-how-to-find-the-price-th
at-maximizes-your-profi
