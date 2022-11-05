# R-code-USP-dissolution
The code estimates the probability of passing USP dissolution test for immediate release dosaage forms.  
User has to enter the value for number of simulations and avg value of sample dissoluton. The number of trials has to be alteast 10000, so that a good approximation of probability of passing can be obtained. Mean value corresponds to the mean of cumulative of drug release at the end of dissolution process for different samples collected during the manufacturing process. Based on these input values, the probability of passing USP dissolution test would be calculated for different standard deviation values (from 1 to 10).  
When higher value (>10000) for number of trials is used, grater precision in the final probability value can be obtained.
