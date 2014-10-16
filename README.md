# BIOMD0000000399: Jenkinson2011_EGF_MAPK

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000399.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000399.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000399 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is a model described in the article:  
**Thermodynamically Consistent Model Calibration in Chemical Kinetics.**   
Garrett Jenkinson and John Goutsias, BMC Systems Biology 2011 May 6;5(1):64.;
PMID: [21548948](http://www.ncbi.nlm.nih.gov/pubmed/21548948) .

ABSTRACT:  
BACKGROUND:  
The dynamics of biochemical reaction systems are constrained by the
fundamental laws of thermodynamics, which impose well-defined relationships
among the reaction rate constants characterizing these systems. Constructing
biochemical reaction systems from experimental observations often leads to
parameter values that do not satisfy the necessary thermodynamic constraints.
This can result in models that are not physically realizable and may lead to
inaccurate, or even erroneous, descriptions of cellular function.  
RESULTS:  
We introduce a thermodynamically consistent model calibration (TCMC) method
that can be effectively used to provide thermodynamically feasible values for
the parameters of an open biochemical reaction system. The proposed method
formulates the model calibration problem as a constrained optimization problem
that takes thermodynamic constraints (and, if desired, additional non-
thermodynamic constraints) into account. By calculating thermodynamically
feasible values for the kinetic parameters of a well-known model of the
EGF/ERK signaling cascade, we demonstrate the qualitative and quantitative
significance of imposing thermodynamic constraints on these parameters and the
effectiveness of our method for accomplishing this important task. MATLAB
software, using the Systems Biology Toolbox 2.1, can be accessed from
www.cis.jhu.edu/~goutsias/CSS lab/software.html. An SBML file containing the
thermodynamically feasible EGF/ERK signaling cascade model can be found in the
BioModels database.  
CONCLUSIONS:  
TCMC is a simple and flexible method for obtaining physically plausible values
for the kinetic parameters of open biochemical reaction systems. It can be
effectively used to recalculate a thermodynamically consistent set of
parameter values for existing thermodynamically infeasible biochemical
reaction models of cellular function as well as to estimate thermodynamically
feasible values for the parameters of new models. Furthermore, TCMC can
provide dimensionality reduction, better estimation performance, and lower
computational complexity, and can help to alleviate the problem of data
overfitting.

This model is a thermodynamically feasible version of a previous model in the
BioModels database, [BIOMD0000000019](http://www.ebi.ac.uk/biomodels-
main/BIOMD0000000019) , described in Computational modeling of the dynamics of
the MAP kinase cascade activated by surface and internalized EGF receptors.
Schoeberl et al (2002), PMID:
[11923843](http://www.ncbi.nlm.nih.gov/pubmed/11923843) .  
The only difference between the present model and the model listed under
BIOMD0000000019 are the values of the parameters.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2012 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


