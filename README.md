# Web-Projects
Function Point Analysis(FPA) is used to make estimate of the software project, including its testing in terms of functionality or function size of the software product.

                                        --**Allan J. Albrecht initially developed function Point Analysis in 1979 at IBM**--
--**The functional size of the product is measured in terms of the function point, which is a standard of measurement to measure the software application.**--

                  Types of FP Attributes:
Measurements------------------------------->Parameters	Examples

1.Number of External Inputs(EI)------------>Input screen and tables

2. Number of External Output (EO)---------->Output screens and reports

3. Number of external inquiries (EQ)------->Prompts and interrupts.

4. Number of internal files (ILF)---------->Databases and directories

5. Number of external interfaces (EIF)----->Shared databases and shared routines.




The Function Point (FP) is calculated with the following formula.

              FP = Count-total * [0.65 + 0.01 * ∑(fi)]
              = Count-total * CAF

where Count-total is obtained from the above Table.

              CAF = [0.65 + 0.01 *∑(fi)]
              
              and ∑(fi) is the sum of all 14 questionnaires and show the complexity adjustment value/ factor-CAF (where i ranges from 1 to 14). 



Example Problem:
Compute the function point, productivity, documentation, cost per function for the following data:

Number of user inputs = 24
Number of user outputs = 46
Number of inquiries = 8
Number of files = 4
Number of external interfaces = 2
Effort = 36.9 p-m
Technical documents = 265 pages
User documents = 122 pages
Cost = $7744/ month
Various processing complexity factors are: 4, 1, 0, 3, 3, 5, 4, 4, 3, 3, 2, 2, 4, 5.


Solution:

Measurement Parameter	Count		                              Weighing factor
1. Number of external inputs (EI)	                          24	*	4 = 96
2. Number of external outputs (EO)	                        46	*	4 = 184
3. Number of external inquiries (EQ)	                      8	*	6 = 48
4. Number of internal files (ILF)	                          4	*	10 = 40
5. Number of external interfaces (EIF) 	                    2	*	5 = 10
----------------------------------------------------------------------------
                                               Count-total → 378
So sum of all fi (i ← 1 to 14) = 4 + 1 + 0 + 3 + 5 + 4 + 4 + 3 + 3 + 2 + 2 + 4 + 5 = 43

                FP = Count-total * [0.65 + 0.01 *∑(fi)]
                = 378 * [0.65 + 0.01 * 43]
                = 378 * [0.65 + 0.43]
                = 378 * 1.08 = 408

Functional Point (FP) Analysis
Total pages of documentation = technical document + user document
                = 265 + 122 = 387pages

Documentation = Pages of documentation/FP
                = 387/408 = 0.94

Cost Per Function = Cost/Productivity = 7744/11.1=700$
