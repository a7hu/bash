This is the tool for creating cs246 test suites.

To execute:

	path/testCaseGen (file contains all test cases)  (test suite name)  (optional - zip file name)
	
Each test case in the test case file must be separated by exactly one empty line.

To generate the test suite, the test case must follow the format of

```bash
<test case 1 .in data>
------------------------
# One can use '# (comment)' to write comment which will be ignored later.
<test case 1 .out data>

<test case 2 .in data>
------------------------
<test case 2 .out data>
------------------------
# or if the .args is needed, then
<test case 2 .args data>

name=<test case 3 name>
# The name of the test case will be default (i.e. testcasefilenameX, X is a digit).
# unless specified as above. 
<test case 3 .in data>
------------------------
<test case 3 .out data>
```
