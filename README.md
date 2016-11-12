This directory contains the tutorial files and slides 
presented for Session 3: Protein preparation, protonation
and building by T. Giorgino and the "bonus track" on Plumed Metric  
presented at the [3rd Workshop on High Throughput Molecular
Dynamics](http://workshop.htmd.org/htmd_molecular_dynamics_programme/)
(2016), 10-11 nov 2016, Barcelona Biomedical Research Parc.

An updated version of this material may be found in the HTMD
distribution.



To run the notebooks non-interactively, use

    jupyter nbconvert --ExecutePreprocessor.timeout=600 --to notebook [name.ipynb]

this will execute the notebooks and store their contents in a
file with .nbconvert.ipynb extension. 

All the notebooks write their output files in directory named as

    <tutorialid>_out_<content>

The "supp" files are supporting information (longer
and/or more advanced topics) which will not be presented as slides.
