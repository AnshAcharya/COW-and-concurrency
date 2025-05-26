
# LAZY™ Corp
OSN Monsoon 2024 mini project 3

## Some pointers
- main xv6 source code is present inside `initial_xv6/src` directory. This is where all the additions/modifications necessary for the xv6 are done. 


## Assumptions
 - Countsort array size of 10^6.
 - Max file name is 10
 - Max similar_frequency (number of instances where files have the same name, id, or timestamp) is 10
 - Maximum files is 100
 - Threshold to use countsort is 42
 - When sorting by name, we are sorting by first 2 characters

 Please note that all these assumptions can be changed via the macros in the beginning of the code.
