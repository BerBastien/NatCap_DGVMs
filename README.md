Code for "Shifting Biomes in a Changing Climate: Unequal Global Impacts on Market and Non-Market Values of Natural Capital"

-Software needed: R. Version the code was tested: R 4.0.2
-Download all large data required and unzip to the folder "Data_External" 
-Main code to generate the impact functions and natural capital variables in: "Code/Compute_PFTs_Climate_change.r"
-To run the "Green" RICE50+ Model, first setup RICE50+ at: https://github.com/witch-team/RICE50xmodel. Activate "natural capital module" and export results as .parquet file. 
-Code to read the results and make the figures: "Code/Process_GreenRICE_Results.r"
-Reproduce all figures of the manusript loading the previously generated data stored in Figures/DataForFigures: "Code/Figures_for_Manuscript.r"

Questions and requests: bbastien@ucsd.edu