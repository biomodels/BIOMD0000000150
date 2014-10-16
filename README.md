# BIOMD0000000150: Morris2002_CellCycle_CDK2Cyclin

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000150.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000150.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000150 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Notes from the original DOCQS curator:  
In this version of the CDK2/Cyclin A complex activation there is discrepancy
in the first curve which plots the binding reaction of CDK2 and Cyclin A
expressed in E. coli. With the published rate constants the simulation does
not match the published graph (Fig.1B) in [Morris MC. et al. J Biol Chem. 277(
26):23847-53](http://www.ncbi.nlm.nih.gov/entrez/query.fcgi?cmd=Retrieve&db=pu
bmed&dopt=Abstract&list_uids=11959850 ) .

Notes from BioModels DB curator:  
Although the parameters are those reported in the table I for CDK2/Cyclin A,
the total fluorescence follows exactly the curve reported in the paper for
CDK2/Cyclin H in figure 1B. Either the plot legend or the table is wrong.


