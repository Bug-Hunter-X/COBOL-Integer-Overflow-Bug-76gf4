# COBOL Integer Overflow Bug

This repository demonstrates an uncommon COBOL bug related to integer overflow.  The `bug.cob` file contains code that performs an arithmetic operation that results in an integer overflow because the result of the calculation exceeds the capacity of the defined data type. This can lead to unexpected and incorrect results.

The `bugSolution.cob` file provides a solution to the issue by using a larger data type capable of holding the expected result.  This highlights the importance of carefully considering the size of data types when performing arithmetic operations, especially when dealing with larger numbers or the potential for results exceeding the intended range.