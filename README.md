# Simulated Annealing Fitting Code 
----------------------------------
### Abinitio QM data is fitted to Ananlytical functional forms

This programme is written to fit interactions between Formaldehyde and Pyrene system. A detailed description of [work is given elsewhere](http://pubs.rsc.org/en/content/articlehtml/2013/cp/c3cp52388h)

* **src** directory has source files 
* **include** directory has necessary Header files
* **tests** directory has sample input files for this programe. They include data from [publication] (http://pubs.rsc.org/en/content/articlehtml/2013/cp/c3cp52388h)


| Functions	       |	Usage						|
|--------------------- | :-----------------------------------------------:	|
| main.cpp	       | Main function						|		
| mc_fitting.cpp       | SIMULATED ANNEALING ALGORITHM AND CHISQ FUNCTION	|	 
| molecule_funcs.cpp   | FUNCTIONS NEEDED TO READ THE ATOMS IN XYZ FORMAT	|	
| potential_funcs.cpp  | 2-BODY POTENTIAL EVALUATION				|	
| damping_fn.cpp       | USES DAMPING FUNCTION WITH 2-body POTENTIAL		|
| molecule.h           | Molecule and Atom data types are defined        	|      
