This are tutorial files for Session 3: Protein preparation,
protonation and building by T. Giorgino. 

To run the notebooks non-interactively, use

    jupyter nbconvert --ExecutePreprocessor.timeout=600 --to notebook [name.ipynb]

this will execute the notebooks and store their contents in a
file with .nbconvert.ipynb extension. 

All the notebooks write their output files in directory named as

    <tutorialid>_out_<content>

To clean the outputs, do

    rm *.nbconvert.ipynb
    rm -rf 03?_out_*      # Be careful!
    
The "supp" files are supporting information (longer
and/or more advanced topics) which
will not be presented as slides.
