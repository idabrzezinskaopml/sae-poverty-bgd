# sae-poverty-bgd
This is a repo for a guide to producing Small Area Estimates (SAE) of poverty using the combination of survey and geo-spatial data, using the example of Bangladesh.

The main file is: Quarto updated BGD geo-spatial covariates process.qmd

Proposed structure for the guide would be:

Audience: 
- Some statistical training
-	Understanding of regression/statistical modelling. 
-	Understanding, previous experience of R/RStudio. 
-	We don’t assume people have any geospatial analysis knowledge/experience. 

1.	Non-technical introduction to the problem
- Relatively short 
- Non-technical explanation of the problem. 
- Exciting. 
- Visual as much as possible. 
- Explain the audience. 
  -  Help decide the reader whether this is for them or not. 
- Explain technical pre-requisites
  - Computing power, etc. 
 
2.	The ‘core’ guide
- How to use this guide. 
  - Each section could be used/gone through on their own (i.e. you can start with Section B, we provide the data output to run that on the Bangladesh example.)
- Section A: Getting the data you need. 
  - Introduction: Non-technical description of what you do in this section. 
    -  Step by step diagram that explains the process. 
  - The theory
    - Key concepts in geospatial analyses
      -  The characteristics of geospatial datasets. 
    - (Step by step)
  - Applying this
    - Data sources
    - Applying R transformations: This is commented code and output from R
  - Caveats/problems/things to look out for. 
- Section B: Producing high-resolution estimates. 
  - Introduction: Non-technical of what you do in this section
    - Diagram
  - The theory
    - Key concepts, assumptions, approaches, references to papers etc. where people can read more. 
  - Applying this 
    - Data sources either use our data or do Section A
    - This is commented code and output from R
      - Step-by-step.
  - Caveats/problems/things to look out for. 

3.	Glossary
4.	FAQ


