# MODEL1303260018: MODEL1303260018

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1303260018.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1303260018.git@20140916`

## Usage

Importing the model package.

`import MODEL1303260018 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Smallbone2013 - Glycolysis in S.cerevisiae - Iteration 18

This model is described in the article:

[A model of yeast glycolysis based on a consistent kinetic characterization of
all its enzymes](http://identifiers.org/pubmed/\[PMID\])

Kieran Smallbone, Hanan L. Messiha, Kathleen M. Carroll, Catherine L. Winder,
Naglis Malys, Warwick B. Dunn, Ettore Murabito, Neil Swainston, Joseph O.
Dada, Farid Khan, Pınar Pir, Evangelos Simeonidis, Irena Spasić, Jill Wishart,
Dieter Weichart, Neil W. Hayes, Daniel Jameson, David S. Broomhead, Stephen G.
Oliver, Simon J. Gaskell, John E.G. McCarthy, Norman W. Paton, Hans V.
Westerhoff, Douglas B. Kell, Pedro Mendes

FEBS Letters _(in press)_

Abstract:

We present an experimental and computational pipeline for the generation of
kinetic models of metabolism, and demonstrate its application to glycolysis in
Saccharomyces cerevisiae. Starting from an approximate mathematical model, we
employ a “cycle of knowledge” strategy, identifying the steps with most
control over flux. Kinetic parameters of the individual isoenzymes within
these steps are measured experimentally under a standardised set of
conditions. Experimental strategies are applied to establish a set of in vivo
concentrations for isoenzymes and metabolites. The data are integrated into a
mathematical model that is used to predict a new set of metabolite
concentrations and reevaluate the control properties of the system. This
bottom-up modelling study reveals that control over the metabolic network most
directly involved in yeast glycolysis is more widely distributed than
previously thought.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1303260018](http://identifiers.org/biomodels.db/MODEL1303260018) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


