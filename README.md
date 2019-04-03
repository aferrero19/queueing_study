# queueing_study
CS 223 project II: Queueing Theory

===============================
Elements to be completed
===============================

// Project specifications:

         + I  Implementation of an event-driven simulator od single server queue system
         + II  Dependence of performance on job variability (variation)
         + III Extended research question
         + IV  Summarize data from experiment II and III

 //I,II
         + How does job size variability affect mean response time in a single-server queueing system?
         
          + System meets the criterion of:
                  - Exponentially distributed job arrival rate (lambda 0-1)
                  - Job size is hyperexponentially distributed (and of balanced means)
                  - if X denotes job size, and X ~ Hyperexp(u,v,p), we will let E[X]=1 and var[X] = {1|10|20|50}
          + Experiments
                  - Measure mean response time for a range of lam. and var(X)
                  
   // Items to be done

           + Solve the system to find E[X] and var[X] (which also means finding u,v and p for our hyperex.)
           + using the results of the preceeding calculation,
                   + write a simulation capable of taking a list of <JOBS> and outputing a <MEAN RESPONSE TIME>
                   + each <JOB> has an <arrival_time> ~ exp(lam.) and <size> ~ hyperex(u,v,p) variable.
                   + Allow room for extended experimentation
           + Take the data from simulation and output CSV file.
           + extend simulation to second experiment.
           + Plot the two data from requesite and extended experiment from CSV files.
           + Write a report summarazing the results from requesite experiment and extented experiment


