# Uninitialized Variable in Ada

This repository demonstrates a potential issue in Ada programming involving uninitialized variables.

The `bug.ada` file contains code with a potential problem where variables are not explicitly initialized.  The `bugSolution.ada` file provides the corrected version. This issue can be easily missed if one is not careful with variable initialization in Ada.  Understanding this is crucial for writing reliable and robust Ada applications.

Ada's strong typing system helps catch many common errors, but uninitialized variables are not directly flagged as errors. Therefore, extra care and testing are necessary to avoid unexpected results.   This example serves as a cautionary tale for proper Ada coding practices.