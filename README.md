##This is code for fitting data published in http://pubs.rsc.org/en/content/articlehtml/2013/cp/c3cp52388h
### THIS PROGRAMME IS WRITTEN WITH FORMAL-PYRENE SYSTEM IN MIND
### TO USE ANY OTHER SYSTEM YOU NEED TO CHANGE THE FUNCTION PART 
### EXCEPT THAT EVERYTHING REMAINS SAME
src/damping_fn.cpp        ---> USES DAMPING FUNCTION WITH 2-body POTENTIAL
src/main.cpp	          ---> MAIN FUCNCTION NEED NOT BE MODIFIED	
src/mc_fitting.cpp        ---> SIMULATED ANNEALING ALGORITHM AND CHISQ FUNCTION 
src/molecule_funcs.cpp    ---> FUNCTIONS NEEDED TO READ THE ATOMS IN XYZ FORMAT	
src/potential_funcs.cpp   ---> 2-BODY POTENTIAL EVALUATION	
include/molecule.h        ---> STRUCTURES SUCH AS MOLECULE AND ATOM ARE DEFINED HERE      
