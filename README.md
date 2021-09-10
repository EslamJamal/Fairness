# COMPAS investigation - Fairness


In this project, we revisit the famous COMPAS dataset by performing data exploration and analysis on the samples to investigate the bias
of the produced compas scores towards certain underlying groups (namely race and gender). Moreover, we train different classifiers to the 
ground truth scores and compare their performance with the compas scores for different groups. We give a closer look into the definition of 
fairness in machine learning and investigate the scores of compas with respect to the different groups, then we utilize a method for calibrating
scores of the classifiers that perturbe the labels so that it produces a more fair predictions (with respect to our definition of fairness). 
At the end, we define metrics to assess the performance of the fairness method used and compute its performance.
