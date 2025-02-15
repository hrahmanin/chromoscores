# Chromoscores

![Alt Text](./docs/representations.png)

A Python package for quantitative analysis of simulated Hi-C maps, providing tools to capture, process and evaluate chromatin interaction patterns such as Topoligically Associating Domains (TADs), flames, and peaks.


### Requirement 📃
- numpy

  
### Structure of the repository
The structure of this repository follows as below:
- maputils : Required functions for processing maps such as obsdrved over expected, or piling up snippets with specific features. 
- scorefunctions : functions for quantitative analysis of features.
- snipping: functions for capturing snippets containing specific features.
- analysis: notebooks and code as tutorials for analyzing simulated data.

  
### Installation 📦
First, 

```
git https://github.com/Fudenberg-Research-Group/chromoscores.git
```
then
```bash
pip install chromoscores
```

## Usage

```py
from chromoscores import base_function
```

### Analysis 📊
Observable features can be quantified, including:

- Observed over expected
- TADs (Topologically Associating Domains)
- flames
- Dots (loops between barriers)

  
See tutorials in `./jupyter_notebooks`.



[![codecov](https://codecov.io/gh/Fudenberg-Research-Group/chromoscores/branch/main/graph/badge.svg?token=chromoscores_token_here)](https://codecov.io/gh/Fudenberg-Research-Group/chromoscores)
[![CI](https://github.com/Fudenberg-Research-Group/chromoscores/actions/workflows/main.yml/badge.svg)](https://github.com/Fudenberg-Research-Group/chromoscores/actions/workflows/main.yml)



