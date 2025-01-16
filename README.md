# Proportion Estimation

Final project for Introduction to Bayesian Statistics course. The aim of the project is to estimate the proportion $p$ of students who sleep more than 8 hours per night.
You can find the complete subject in the "Final_Project_Subject.pdf" document.

## Comparison of 3 models

2 envisaged priors on the parameter $p \in ]0,1[$ and one uninformative prior:

- Model A : discrete distribution defined by
  i | $b_i$ | $\mathbb{P}(p = b_i)$ 
  :---:|:-------:|:----------------------:
   1  | 0.05  | 0.03                 
   2  | 0.15  | 0.18                 
  3  | 0.25  | 0.28                 
   4  | 0.35  | 0.25                 
   5  | 0.45  | 0.16                 
  6  | 0.55  | 0.07                 
   7  | 0.65  | 0.03

- Model B : Beta distribution with parameters $a = 3.4$ and $b = 7.4$
- Model C : Uninformative Jeffrey's prior
                                   
