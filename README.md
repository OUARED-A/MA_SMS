# A Systematic Mapping Study of Model Animation for MDE:
We propose a Systematic Mapping Study (SMS) to help understand what challenges, technical difficulties and current implementation techniques have been used for animation. Our SMS presents serving a guide for practitioners and researchers for understanding the approaches, the languages and tools used for animation. 

![image](https://user-images.githubusercontent.com/42803883/182678685-3b242f3b-ac38-479f-ab71-768f96a45954.png)

# About CORPUS Exploration and Analysis:

To allow independent replication and verification of our study, the accompanying online repository is publicly available,
includes the _Python_ scripts we developed for data exploration and analysis.

## Setup and Run:

### Requirements:

[![PyPI](https://img.shields.io/pypi/pyversions/pylearning.svg)]()

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/weiji14/deepbedmap/]

-You may need to install _Python 3.3_ or higher with and _Matplotlib_, also you can use online solution like Google Colab Notebooks (https://colab.research.google.com/)

*  Python 3.3: https://www.python.org/downloads/release/python-330/

*  Matplotlib: https://matplotlib.org/stable/users/installing/index.html

*  Google Colab Notebooks: https://colab.research.google.com/


### Installation and Run:

1. Download script.zip file a zip from Github

2. Create script folder anywhere on your PC and extract zip content to this folder

3. Customize the path of the CORPUS folder to read a CSV file (line of code 9 ->  ``` data = pd.read_csv('CORPUS-Final.csv')```)

4. Run a python script to get all resultats of vertical and orthogonal analysis.

5. All Results Plots are visualized in the Python execution environment and exported as a pdf file in the current folder. 

![image](https://user-images.githubusercontent.com/42803883/169172339-a9d15569-2827-486c-ab91-611ea6832925.png)
