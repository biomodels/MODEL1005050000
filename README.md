# MODEL1005050000: Salazar2009_PhotoperiodicRegulation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1005050000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1005050000.git@20140916`

## Usage

Importing the model package.

`import MODEL1005050000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Prediction of photoperiodic regulators from quantitative gene circuit models.**   
Salazar JD, Saithong T, Brown PE, Foreman J, Locke JC, Halliday KJ, Carré IA,
Rand DA, Millar AJ _Cell_ 2009 Dec; 139(6): 1170-9
[20005809](http://www.ncbi.nlm.nih.gov/pubmed/20005809) ,  
**Abstract:**   
Photoperiod sensors allow physiological adaptation to the changing seasons.
The prevalent hypothesis is that day length perception is mediated through
coupling of an endogenous rhythm with an external light signal. Sufficient
molecular data are available to test this quantitatively in plants, though not
yet in mammals. In Arabidopsis, the clock-regulated genes CONSTANS (CO) and
FLAVIN, KELCH, F-BOX (FKF1) and their light-sensitive proteins are thought to
form an external coincidence sensor. Here, we model the integration of light
and timing information by CO, its target gene FLOWERING LOCUS T (FT), and the
circadian clock. Among other predictions, our models show that FKF1 activates
FT. We demonstrate experimentally that this effect is independent of the known
activation of CO by FKF1, thus we locate a major, novel controller of
photoperiodism. External coincidence is part of a complex photoperiod sensor:
modeling makes this complexity explicit and may thus contribute to crop
improvement.

  

**Note:**

There are four models described in the paper. This model corresponds to model
3 (which is a combination of model 1 and model 2). The SBML file is
redeveloped from Kevin S

This model is same as
[BIOMD0000000055](http://www.ebi.ac.uk/biomodels/BIOMD0000000055) , but with
revised light function.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


