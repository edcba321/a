The CI testing history contains the following fields:

projectName: the name of this project;
commitId: the hash of this commit;
buildNum: the Id of building in this CI testing;
buildDate: the date for this CI testing;
duration: the time (millisecond) to run all test cases in this CI testing;
buildResult: 1 means pass, 0 means failed;
totalCount: the number of test cases in this CI testing;
failCount: the number of failed test cases in this CI;
testClassName: the name of class in the current row;
testFunctionName: the name of test case in the current row;
status: the result of the current test case, 1 means pass, 0 means failed;
subduration: the time (millisecond) to run the current test case;
isskipped: 0 means not skipped, 1 means skipped.