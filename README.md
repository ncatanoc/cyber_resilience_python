# Cyber Resilience for Python

This repository includes (a) two Event-B models for vehicle platooning, which can be imported from the Rodin IDE version 3.5; (b) a *Jupyter Notebook* with a formal verification framework in Python with an encoding for safety and liveness properties and a formal model for vehicle platooning manually ported from Event-B.

## Event-B models for platooning
Files *rodin_platooning.zip* and *rodin_platooning_simplified.zip* are two Rodin project files. They can be imported in Rodin version 3.5 (File, Import, Existing Projects into Workspace).  

## Unit Testing
File *eclipse_single_platooning* is an Eclipse project that contains manually-written unit tests for the platooning system. We used the EventB2Java code generator to generate Java code from the Event-B model of platooning. 

## Jupyter Notebook 
File *B2Py.ipynb* is a formal verification framework for Python. It can be imported from Google Colab or JupyterLab.
