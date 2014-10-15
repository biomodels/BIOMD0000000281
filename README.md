# BIOMD0000000281: chance

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000281.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000281.git@20140916`


# Model Notes


This model is described inthe article:  
**Metabolic control mechanisms. 5. A solution for the equations representing interaction between glycolysis and respiration in ascites tumor cells.**   
Britton Chance, David Garfinkel, Joseph Higgins and Benno Hess, _J Biol Chem._
1960 35:2426-2439. PubmedID:
[13692276](http://www.ncbi.nlm.nih.gov/pubmed/13692276)  
Abstract:  
The other papers of this series present experimental evidence for possible
relationships between the kinetics of oxygen, glucose, adenosine diphosphate,
adenosine triphosphate, and phosphate and those of the cytochromes and
pyridine nucleotides of the ascites tumor cell. From these general experiments
we are able to formulate, under the law of mass action, a minimum hypothesis
under which the four metabolic regulations previously described can be
observed. In brief, the system can be represented by the known enzyme systems,
a relatively higher ADP affinity in respiration than in glycolysis, the
mitochondrial membrane, a segregation of ATP into two compartments, and an
ATP-utilizing system that is responsive to small decreases of the
intracellular ADP level. The chemical equations for the pathway from glucose
to oxygen are solved by a digital computer method so that the responses of the
chemical equations and of the living cell can be accurately compared.  
For reasons already described, we greatly prefer a com- puter representation
based upon a physical or chemical law representing the action of the system to
a model simulating the operation of the chemical system but not based upon
funda- mental laws for the reactions involved; such a representation would not
adequately represent the kinetics of the system, as in an electric circuit
network or in some types of hydraulic ana- logues.

The model gives solutions of the reaction kinetics for three types of
metabolism:

  1. 0 - 64s, metabolism of endogenous substrate
  2. 64s - 119s, metabolism of added glucose, illustrating the activated and inhibited aspects of glucose metabolism
  3. 119s - 153s, relief of glucose and oxygen inhibition by the addition of an uncoupling agent

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html) .  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


