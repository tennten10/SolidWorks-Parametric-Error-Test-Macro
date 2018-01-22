# SolidWorks-Parametric-Error-Test-Macro
This macro was written to test for rebuild errors when given parameters within the design space for a part. It was written for a specific assembly and set of parts, but can be generalized with a couple modifications to an excel file and the code. Finding rebuild errors greatly helps in designing a robust part that can handle easy changes without requiring significant time commitment later on.

This project was set up with one .txt file driving the variables for several parts simultaneously within an assembly. The parts within the assembly then automatically adjust equation driven variables to create features that work together seamlessly with consistent clearances, wall thicknesses, etc. 

Testing parameters were set up within an excel file that lays out parameter combinations and records how many rebuild errors or warnings, the part(s) it occurs on, the feature name, the error code, and whether the parts in the assembly interfere with each other anywhere. These rebuild and functionality checks assisted in creating an assembly that was extremely robust and almost entirely equation driven. 

To protect intellectual property, variable names, parts, and assemblies were changed. This is a generalized version that requires modification. Look for "/* ****** */" to see where edits should be made to alter this to your purposes.  
