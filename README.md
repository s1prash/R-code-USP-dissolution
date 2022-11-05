# R-code-USP-dissolution
The code estimates the probability of passing USP dissolution test for immediate release dosaage forms.  
User has to enter the value for number of simulations and avg value of sample dissoluton. The number of trials has to be alteast 10000, so that a good approximation of probability of passing can be obtained. Mean value corresponds to the mean of cumulative of drug release at the end of dissolution process for different samples collected during the manufacturing process. Based on these input values, the probability of passing USP dissolution test would be calculated for different standard deviation values (from 1 to 10).  
When higher value (>10000) for number of trials is used, greater precision in the final probability value can be obtained.  
The repository contains the following files (a) stdev_*.csv : Simulated raw data
(b) All stages stdev_*.csv : Lists the passing or failing at each stage (pass = 1, fail =0)
(c) Fail trials.csv : List all the trials which fail to meet acceptance criteria at all standard deviations
(d) Final.csv : List of meeting acceptance criteria probability at all stages
(e) Std dev *.pdf : Plot of cumulative probabilities as function of trial count (* different standard deviation values).  
Users can request support by opening an issue on GitHub
