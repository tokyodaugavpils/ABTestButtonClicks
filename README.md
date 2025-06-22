A/B Test: Button Clicks

A simple A/B testing simulation project to analyze whether a new button design increases user conversion.

⸻

Project Overview

This project simulates a real-world A/B testing scenario: testing whether a new button design on the Yandex homepage improves the click-through rate (CTR). It helps you understand the process of running an experiment, generating synthetic data, and checking for statistical significance using Python.

The concept mimics experiments conducted by major tech platforms like Yandex, Google, and Netflix to make data-driven UI decisions.

⸻

Dataset

No real data is used — we generate synthetic (simulated) data for both groups:
	•	Group A (Control): Sees the original button
	•	Group B (Test): Sees the new button

For example:
	•	Group A conversion rate: 5%
	•	Group B conversion rate: 6.5%

Each group contains 5000 simulated users.

⸻

Goal

To determine whether the new button design significantly improves user clicks, using statistical methods.

This kind of test is useful for:

•	Website interfaces
 
•	App UX improvements
 
•	Email campaigns
 
•	In-product experiments

⸻

Skills Demonstrated

•	Generating synthetic A/B testing data
 
•	Visualizing group differences using seaborn/matplotlib
 
•	Performing a t-test to compare conversion rates
 
•	Calculating confidence intervals 

•	Interpreting p-values and statistical significance

⸻

Tools & Libraries
	
•	numpy — random data generation (binomial distribution)
 
•	pandas — data structuring

•	matplotlib + seaborn — plots and visuals

•	scipy.stats — statistical testing (ttest_ind)

⸻

File Description

    abtest1.ipynb
    abtest2.ipynb
    
    
