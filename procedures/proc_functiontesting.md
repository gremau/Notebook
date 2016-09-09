###### Testing data analysis functions

Code used in data analysis can perform fairly complex operations on
datasets and generate output that may be significantly changed from the
original data. The code itself can also be fairly complex and its actual
function may be difficult to discern just by reading the code or looking
at the data. It is important to verify that the result of running this
code is what is expected and that the output is accurate. Writing test
functions that call data analysis code and analyze their output is a
useful way to do this.

##### Matlab

In Matlab, testing scripts are generally put in a "functiontesting"
subdirectory. When it is time to run the tests, add this path
(*addpath('./functiontesting')*) and then run the test scripts from the
commandline.