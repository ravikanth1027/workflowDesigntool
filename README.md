The tool contsists a single pyhton file workflowDesgin_tool.py. 

Presequities:
1. Python 3

Modes of Execution:
The tool runs in two modes 
1. File Mode and 
2. Manual Mode.

File Mode: In this mode the tool expects one input file as commandline argument.
The input file should contain the commands to describe the protocol. Sample input file ns.txt is available with the code. Once the tool executes all the commands from the input file, it prompts the user to either provide more commands or to exit the execution.

Manual Mode: In this mode the user should provide all the commands to design the workflows. Execution can be interrupted by providing command 'exit'.

Commands to Execute:

> python3 workflowDesgin_tool.py
