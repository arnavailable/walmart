# walmart
Multi-Armed Bandit algorithms (Epsilon Greedy, Thompson Sampling using Beta Distribution) to analyze 4th of July retail strategies.

# UCLA Dataset

| Column   | Description                                                                                             |
|----------|---------------------------------------------------------------------------------------------------------|
| `user_id`| Unique anonymous user identification                                                                     |
| `date`   | The date the event happened                                                                              |
| `arm`    | The marketing strategies. The team assigns the most website traffic to `arm_3`, the least to `arm_1`, and `arm_2` in between |
| `click`  | Binary outcome where `0` indicates no click and `1` indicates a click                                    |

## File Name
**UCLA_dataset**

eCommerce Holiday Homepage Optimization Dataset
In preparation for the upcoming holiday (4-th of July), the marketing team comes up with three marketing strategies and collects a dataset on 06-30-2024 prior to the launch. Based on their past expertise, the team assigns the most website traffic to arm 3, the least to arm 1, and arm 2 in between. 
Here is the detailed information about the dataset: 
	•	user_id: unique anonymous user identification
	•	date: date the event happened
	•	arm: the three marketing strategies. arm_1 for the first strategy, etc.
	•	click: 0 for no clicks and 1 for clicks
As a data scientist, you must help the team answer the following question:
	•	what is the best website traffic split among these three arms?

Requirements/Hints
	•	The business is not interested in knowing which arm is statistically different from the others. The goal is to optimize the holiday traffic and minimize the loss/cost.
	•	All recommendations have to back up with data.
	•	Look into two Multi-Armed Bandit algorithms: 
	•	Epsilon Greedy
	•	Thompson Sampling using Beta Distribution
	•	Check the following resources: 
	•	Stitch Fix, https://multithreaded.stitchfix.com/blog/2020/08/05/bandits/
	•	A modern Bayesian look at the multi-armed bandit by Google, https://sites.socsci.uci.edu/~ivan/asmb.874.pdf 
