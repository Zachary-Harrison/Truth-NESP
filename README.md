# Protein Melting Temperature Prediction

This project is based on the Kaggle competition [Novozymes Enzyme Stability Prediction](https://kaggle.com/competitions/novozymes-enzyme-stability-prediction), where the goal was to predict the melting temperatures of proteins based on their structure. We used three different model types to make these predictions, each with its unique approach and data preprocessing steps:

1. A simple method that just looked at the sequence of the proteins.
2. A more complex method that used a 2D image of the proteins' physical and chemical properties.
3. An even more complex method that used a 3D image of the proteins' unique features.

The competition didn't just look at how close our guesses were to the actual temperatures. Instead, it looked at how well we could rank the proteins from lowest to highest melting temperature. 

Interestingly, we found that we made the most progress not by changing our guessing methods, but by changing the data we used to make our guesses. 

For more information, read our [report](FinalReport.pdf) on the subject, now with IEEE style!

# References

- [Truth](https://github.com/Zachary-Harrison/cs5665-Truth)
  - Authors: Keldon Boehmer, Zachary Harrison
  - Year: 2022

- [Novozymes Enzyme Stability Prediction](https://kaggle.com/competitions/novozymes-enzyme-stability-prediction)
  - Authors: Dennis Pultz, Esben Friis, HCL-kanishkaa, Jesper Salomon, Maggie, Peter Fischer Hallin, Sarah Baagøe Jørgensen, Walter Reade
  - Year: 2022

- [RMSD from Molecular Dynamics](https://www.kaggle.com/code/oxzplvifi/rmsd-from-molecular-dynamics)
  - Author: Oscar Villarreal Escamilla
  - Year: 2022

- [NESP: relaxed rosetta scores](https://www.kaggle.com/code/shlomoron/nesp-relaxed-rosetta-scores)
  - Author: greySnow
  - Year: 2022

- [NESP: AlphaFold+GetArea exploration](https://www.kaggle.com/code/roberthatch/nesp-alphafold-getarea-exploration)
  - Author: Robert Hatch
  - Year: 2022

- [pLLDT, DDG, demask, sasa](https://www.kaggle.com/code/kvigly55/plldt-ddg-demask-sasa)
  - Author: kvigly
  - Year: 2022

- [Aminoacids: Physical and Chemical Properties](https://www.kaggle.com/datasets/alejopaullier/aminoacids-physical-and-chemical-properties)
  - Author: moth
  - Year: 2022

- [NOVO ESP – ELI5 - Performant Approaches [LB=0.451]](https://www.kaggle.com/code/dschettler8845/novo-esp-eli5-performant-approaches-lb-0-451)
  - Author: Darien Schettler
  - Year: 2022

- [14656 Unique Mutations+Voxel Features+PDBs](https://www.kaggle.com/code/vslaykovsky/14656-unique-mutations-voxel-features-pdbs)
  - Author: Vladimir Slaykovskiy
  - Year: 2022

- [NESP: ThermoNetv2](https://www.kaggle.com/code/vslaykovsky/nesp-thermonet-v2)
  - Author: Vladimir Slaykovskiy
  - Year: 2022