# Automated-Testing-Kit
Automated Testing Kit including the automated fuzz testing, mutation testing, debugging, etc. This repository encompasses a range of software testing tools and methodologies designed to enhance the robustness and reliability of software across multiple languages.****


## Highlights
### Comprehensive Test Suites: 
Developed tests across Python, C, and Java focusing on applications like AVL Trees, PNG Graphics, and Data Visualization.

### Automated vs Manual Testing: 
Utilized tools such as American Fuzzy Lop and EvoSuite to gauge the efficiency of automated test suites in comparison to manual ones, focusing on programs like pngtest and the jsoup Java library.

### Mutation Testing Tool: 
Crafted a Python-based tool using abstract syntax trees (AST), harnessing the ast and astor modules. This tool produces mutant variations of programs to test the resilience of test suites.

### Diverse Mutation Operators: 
Implemented several mutation strategies, including:

Negating comparison operations
Swapping binary operators
Conditionally deleting certain statements
All the while ensuring consistent and deterministic program outputs.

### Static Analysis with Facebook's Infer: 
Conducted static code analysis using Facebook's Infer on projects like lighttpd webserver and jfreechart-1.5.0, aiming to pinpoint defects and drawing parallels with documented security vulnerabilities.

### Delta Debugging: 
Integrated the Delta Debugging algorithm in Python to streamline the process of identifying the root causes behind software anomalies. Also utilized for test suite minimization while retaining essential coverage.

### Troubleshooting and Collaborative Efforts: 
Proactively addressed tool setup challenges and collaborated effectively to troubleshoot issues, ensuring optimal execution across varied software testing methodologies.
