This is the tool for creating cs246 test suites
To execute:
	./testCaseGen <file contains all test cases> <test suite name> <optional - zip file name>
Each test case in the test case file must be separated by exactly one empty line.
To generate the test suite, the test case must follow the format of

<test case 1 .in data>
------------------------
<test case 1 .out data>

or if the .args is needed, then

<test case 1 .in data>
------------------------
<test case 1 .out data>
------------------------
<test case 1 .args data>

One can use '# <comment>' to write comment which will be ignored later.
