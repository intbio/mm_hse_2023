# Workshop: Protein structure modelling in Modeller

## Description
- We will obtain protein structure based on templates
- Duration: 60 minutes
- Objectives: be able to 
    - Prepare protein sequences for Modeller.
    - Select a template based on sequence identity comparison.
    - Align target sequence with the template
    - Model building.
    - Model evaluation.
    - CollabFold usage 
    - AlphaFold2 application using ChimeraX 

## Jupyter notebook
- [modeller.ipynb](modeller.ipynb)

## AlphaFold2  
- [Collab notebook](https://colab.research.google.com/github/deepmind/alphafold/blob/main/notebooks/AlphaFold.ipynb)
- [CollabFold paper](https://www.biorxiv.org/content/10.1101/2021.08.15.456425v2)
- [ChimeraX example](https://www.youtube.com/watch?v=le7NatFo8vI&ab_channel=UCSFChimeraX)

## Swiss-Model  
- [Web server]([https://colab.research.google.com/github/deepmind/alphafold/blob/main/notebooks/AlphaFold.ipynb](https://swissmodel.expasy.org/))

## Required software and resources
- Access to a Jupyter notebook evironment with Python 3, modeller, MDanalysis, nglview, Bio libraries 
- Access to Google collab with GPUs
- To install modeller run in your conda environment "conda install -c salilab modeller", use license key "MODELIRANJE"

## Learning resources
- [Modeller tutorial](https://salilab.org/modeller/tutorial/)
- [Swiss-Model tutorial](https://swissmodel.expasy.org/docs/examples)
- [DOPE (Discrete Optimized Protein Energy) method](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2242414/pdf/2507.pdf)

## Assignments

Modeller (based on tutorial)
1. Build model for lactate dehydrogenase from Trichomonas vaginalis (TvLDH) based on a single template. Perfom loop refine by LoopModel, DopeLoopModel. 
2. Compare plots of energy score (DOPE) for model, template, model with auto loop refine, model with Dope loop refine.

AlphaFold2 
1. Predict 3D structure of your protein (choose small one or fragment); use one of ChimeraX or Collab. Add sequence coverage plot and structure image.  


### Troubleshooting
- Consult with the seminar protocol/recording
- Ask questions in Slack
