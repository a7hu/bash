This is the tool for creating cs246 test suites
To execute:
	./testCaseGen <file contains all test cases> <test suite name> <optional - zip file name>
To generate the test suite, the test case must follow the format specified below, and each test case must be separated by exactly one empty line. 
A sample test case file is included within the ****:
********************************************************************************************************
name=<test case name> # This line is optional. If the test case name is not specified, use default name
{test case 1 .in file data
 .
 .
 .
}
-----------------------------
{test case 1 .out file data
 .
 .
 .
}
------------------------------
# This is a comment which will be ignored
# Note: if there is not .args needed, don't include it in the test case
{.args file data
 .
 .
 .
}
------------------------------

{test case 2 .in file data 
 .
 .
 .
}
-----------------------------
{test case 2 .out file data
 .
 .
 .
}

{test case 3 .in file data 
 .
 .
 .
}
-----------------------------
{test case 3 .out file data
 .
 .
 .
}
********************************************************************************************************


