# C-GSGP
The optimized implementation of paper "Competent Geometric Semantic Genetic Programming for Symbolic Regression and Boolean Function Synthesis". The original code can be downloaded from the link in the paper.


There are several changes in my project:  
1)I complement an example parameter file based on Nguyen7 problem, which means you can get an easy start with ECJ and the new classes designed by Tomasz et al.  
2)The termination condition in my project has been changed to the number of node evaluation (NNE).  
3)I update the hit criterion in ec.app.semanticGP.Regression.evaluate().  
4)I add more statistic outputs item for the project. It helps you to get a detail analysis with C-GSGP. The outputs include the best program so far, the test error and the number of program nodes of the best program, the evaluation times, and the success criterion (train error < 1e-4).    

How to use this project?  
Preliminary work: Install Java JRE 1.8 or higher.  
1) Download the original source code from the link of the paper.    
2) Download the JAR bag and .params file in this project.  
3) Build the JAR bags (including the JAR bags of the original source code) into the Java project.  
4) Add the .dll of lpsolver55j (in the orignial source code) to the path of JAVA.  
5) Update the corresponding file path of the .params file, so that it can find its parent .params and set up the database.  
