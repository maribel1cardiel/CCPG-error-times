# CCPG-error-times

Install gitpython, dateutil, numpy, and matlablib before hand

Directions:
1.  clone own repository
2.  to run on different repository change directory(line 4) and title(line 76)

Description
The code creates a complimentary cumulative probability graph of code error lifespans in a repository. The code iterates through the repository looking for a revert, finding the commit that introduced the error, finds the time difference between the two and returns a CCPG of times. Throughout the code, it run functions that:
1.	look for the word “revert” in the messages of the repository
2.	finds the string hexsha affiliated with the commit that introduced the error
3.	finds the commit that corresponds to string hexsha
4.	finds the time difference between the initial commit and the reverted commit
5.	creates a complimentary cumulative probability graph from the times collected 

Motivation:
The purpose of this code is to analyze different repository error lifespans.
