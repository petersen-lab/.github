# Welcome to the Petersen Lab GitHub repositories 👋

## 👩‍💻 Useful resources
* petersen-lab-book

## 🌈 Contribution guidelines - new users

### Projects
Create a private repository for your projects

# Matlab code for the PetersenLab at UCPH 
Dependencies and other related tools

## Repositories
### Our repos
* petersen-lab-matlab (do we want a better name?)
* CellExplorer
* Kilosort3Wrapper
* petersen-lab-python 

### Third-party repositories
* Buzcode
* KiloSort
  
### Matlab apps (dependencies)
* Curve Fitting Toolbox (required by CellExplorer): https://se.mathworks.com/products/curvefitting.html
* Signal Processing Toolbox (required by CellExplorer): https://se.mathworks.com/products/signal.html
* Statistics and Machine Learning Toolbox (required by CellExplorer): https://se.mathworks.com/products/statistics.html
* Parallel Computing Toolbox (optional, allows for parallel processing of certain features): https://se.mathworks.com/products/parallel-computing.html
* Image Processing Toolbox (optional for NeuroScope2, allows for selection of channels from the probe layout): https://se.mathworks.com/products/image.html
* DSP System Toolbox (https://se.mathworks.com/products/dsp-system.html) or the Audio Toolbox (https://www.mathworks.com/products/audio.html) (optional for NeuroScope2 to stream audio of traces).

## File naming convention for raw and derived data
We will follow the CellExplorer data structure and format:  https://cellexplorer.org/datastructure/data-structure-and-format/


### General Principles for naming variables, functions and scripts
- **Consistency**: Stick to the chosen convention throughout the codebase.
- **Avoid Abbreviations**: Unless widely recognized or obvious, avoid abbreviating variable names.
- **Meaningful Names**: Prioritize meaningful and descriptive names over short, cryptic ones.

| Names                          | Naming Convention               | Examples            |
|--------------------------------|---------------------------------|---------------------|
| **Variable Names**             | Lower Camel Case                | `variableNames`     |
| **Function Names**             | Lower Camel Case                | `functionNames`     |
| **Script Names**               | Lowercase with Underscores      | `script_names`      |
| **Class Names**                | Upper Camel Case                | `ClassNames`        |
| **Struct Fields**              | Lower Camel Case                | `structFields`      |
| **Temporary Variables**        | Short and Contextual            | `temp`              |
| **Loop Indices**               | Single Letters if span is short scope, otherwise please use meaning full names  | `i` and `iShank`   |
| **Logical (Boolean) Variables**| Prefix with is, has, can, should, etc. | `isValid`    |

# Python

### Guideline for Python
PEP8: https://peps.python.org/pep-0008/
