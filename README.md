#      Blood Mitochondrial Heteroplasmic Mutations and Cognitive Performance in Late Midlife: The REGARDS Study

This project analyzes how heteroplasmic mutations in mitochondrial DNA (mtDNA) are associated with cognitive performance in late midlife,
using data from the REasons for Geographic and Racial Differences in Stroke (REGARDS) study. 
The goal is to explore the role of mtDNA in early cognitive decline, which may be linked to Alzheimer’s risk and other forms of cognitive impairment.


# Contents
- Installation
- Usage
- Project Structure
- Dependency Requirements
- License
- Contact


# Installation
- Clone this repository:
git clone https://github.com/username/repository.git
- Navigate to the directory:
cd repository
- Install dependencies:
Use RStudio to load and run the scripts. Package requirements for R are listed in the Dependency Requirements section.


# Usage
Running the Script

The main analysis includes:
- Assessment of mtDNA mutation profiles in blood through deep sequencing.
- Statistical models to study associations between mtDNA mutation load and cognitive performance, adjusted for racial and geographic factors.
- Volcano plots of the associations resulting from the statistical models.
  
Steps to run the analysis:
- Load the scripts in RStudio, ensuring that the data files are in the specified directory.
- Run the main script (mtDNA_cognition_analysis.R), which contains sections for mutation load analysis and cognitive performance associations.


# Project Structure
src/: R scripts for mtDNA mutation and cognition analysis.
data/: Directory for input data files.
results/: Generated analysis results and visualizations.
README.md: Project description and instructions.
LICENSE: Project license.


# Dependency Requirements
Ensure that you have the following R packages installed:
install.packages(c("dplyr", "lmerTest", "ggplot2", "reshape2"))

# License
This project is licensed under the MIT License. See the LICENSE file for more details.

# Contact
Developed by Dr. Prada. For questions or suggestions, email diddier.prada@mountsinai.org.
