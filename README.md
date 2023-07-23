# MADAME
![madame_workflow](https://github.com/Biome-team/MADAME/assets/130676054/0283f38f-d188-4348-93ea-b98379d4c4b8)

Project overview
----------------
MADAME is a bioinformatic tool designed to facilitate and automatize data and metadata retrieval from ENA database.
This open-source user-friendly project, written in Python 3.11, enables users to enrich downloaded metadata with related publications and view the results through a report before downloading data. With its flexible workflow, MADAME helps users save time and resources.

MADAME has 4 principal FUNCTIONS:

* METADATA RETRIEVAL

* PUBLICATIONS RETRIEVAL

* REPORT GENERATION

* DATA RETRIEVAL

Installation instructions in a nutshell
-------------------------
Please visit the **examples** directory of this Github page for a step-by-step installation and example usage.

**1. DOWNLOAD Python 3:**

https://www.python.org/

**2. INSTALL EXTERNAL LIBRARIES:**

To install external libraries open a terminal (prompt for windows users) and navigate to the MADAME folder with the following:
* cd path/to/MADAME
* cd path\to\MADAME (windows-users)

Now that you are inside the MADAME folder, if you are a conda user (best option), run the following command:
* conda env create -f requirements.yml

Otherwise (less recommended), run the following command:
* pip3 install -r pip_requirements.txt

How to run MADAME
------------------
Open a terminal and go to the MADAME directory by running the entire path:

linux and mac:

* cd path/to/MADAME

windows (prompt):

* cd path\to\MADAME

Now that you are in the right directory, run the following command to start:

* python main_madame.py
