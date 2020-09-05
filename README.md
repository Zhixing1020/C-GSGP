# C-GSGP
The optimized implementation of paper "Competent Geometric Semantic Genetic Programming for Symbolic Regression and Boolean Function Synthesis". The original code can be downloaded from the link in the paper.


There are several changes in my project:
1)I complement an example parameter file based on Nguyen7 problem, which means you can get an easy start with ECJ and the new classes designed by Tomasz et al.
2)The termination condition in my project has been changed to the number of node evaluation (NNE).
3)I update the hit criterion in ec.app.semanticGP.Regression.evaluate().
4)I add more statistic outputs item for the project. It helps you to get a detail analysis with C-GSGP. The outputs include the best program so far, the test error and the number of program nodes of the best program, the evaluation times, and the success criterion (train error < 1e-4). 
