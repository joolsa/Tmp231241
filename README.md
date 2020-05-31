Hello!

This repository contains the necessary files for replicating the methodology in 
[PAPER UNDER REVIEW].

NOTE: The data files are scrambled to protect business-sensitive information, and thus provide an example of data structure rather than real data. To generate meaningful personas, the data files should be replaced with real data obtained from YouTube Analytics or other compatible source.

==INSTRUCTIONS==

You can install the libraries required to run the code by using this command:

pip install -r requirements.txt

The replication of the methodology involves four steps. The steps are explained as follows.

STEP 1: Download the example dataset: https://drive.google.com/file/d/1DdXcZCdS3T9hgS4Qp844ky3q0cJfn4Lm/view?usp=sharing
STEP 2: Decompose the personas:

Persona decomposition.ipynb -- this file contains the necessary code for decomposing the example dataset.
Decomposition results in two files that are required for persona generation (normal and transposed file).

STEP 3: Submit your decomposed files (normal and transposed) to Automatic Persona Generation [1]. Contact point: Dr. Joni Salminen, email: jsalminen@hbku.edu.qa.

STEP 4: You will receive back files corresponding to contents of the "personas" folder.
You can then evaluate the personas in these files using the file:

Persona evaluation.ipynb -- this file contains the necessary code for evaluating Persona Diversity, Fairness, and Consistency (DFC).

====

[1] More information about Automatic Persona Generation: https://persona.qcri.org
