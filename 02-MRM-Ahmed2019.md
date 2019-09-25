# PROJECT: MRM paper - Ahmed & Levesque 2019

## GENERAL DESCRIPTION 
### Aim
Create an interactive Jupyter Notebook that supplements a paper in the journal called Magnetic Resonance in Medicine, titled "Pharmacokinetic modeling of dynamic contrast‐enhanced MRI using a reference region and input function tail" by authors Zaki Ahmed, Ives R. Levesque.

### Type	
* [x] Educational document (i.e. interactive tutorial) 
* [x] Supplementary material for a published paper  
* [x] Research report 
  * [x] Includes data 
  * [x] Includes simulations
  * [x] Includes analytical equations 
  * [ ] Includes statistical analyses
  * [x] Re-generates already existing figures 
  * [x] Makes use of open-source software 
  * [x] Makes use of open-source scripts

### Topic
Dynamic contrast‐enhanced MRI (MRI: Magnetic Resonance Imaging)

### Keywords 
Arterial input function, cancer, Dynamic Contrast‐Enhanced (DCE)‐MRI, perfusion, pharmacokinetics, reference region model

### Resources
* Paper
  * https://onlinelibrary.wiley.com/doi/abs/10.1002/mrm.27913
* Source code
  * https://github.com/MPUmri/RRIFT 
* Data
  * https://osf.io/wr3kf/files/ 

### Additional tools

* [Plot.ly](https://plot.ly)
* [SoS](https://vatlab.github.io/)
* [Jupyter Book](https://jupyter.org/jupyter-book/intro.html)

## Pros & Challenges   

### Pros
* Carefully written scripts to reproduce all data figures of paper.
* Offers saved simulation data to avoid lengthy computation, but also the simulation scripts to reproduce them.

### Challenges
* MATLAB code likely can’t be converted to Octave, so will have to run Jupyter notebooks with the MATLAB kernel.
  * There are too many MATLAB functions missing from Octave that are needed, or some that are implemented differently.
  * Because of that, won’t be able to run on Binder.
* Will need to have a local MATLAB license (MATLAB  version >= 2014b)

## TENTATIVE EXPECTATIONS  

Using the code, data, and scripts supplied by the authors of this journal paper, create a (or several) Jupyter Notebook(s) that supplements the paper, such that can reproduce the figures easily in this environment. Some text between the figures should be present (either for explanations or to transition between figures). Additionally, figures should have the 
added feature of being interactive using Plot.ly. Lastly, the Jupyter Notebook should be exported into a clean HTML format, either using the native SoS export to HTML feature or Jupyter Book.

## YOUR REPOSITORY MUST HAVE 
* LICENSE 
* README
* Configuration files or Dockerfile 
* .gitignore
* Setup instructions
* … 

## YOUR REPOSITORY SHOULD NOT HAVE 
* Binary data (simple png files etc are OK) 
* Output html figures > 1MB 

You can upload such files to a public OSF repo (having the exact same name with your GitHub repo) and download them to your environment. 

## TO BE FILLED OUT BY THE NOTEBOOK CREATOR 

**Name and Surname:** 

**GitHub username:** @... 

**GitHub repository where the notebook is hosted:**  .../...

**Link to exported the exported HTML website:**  .../...

**Environment is resolved by:** 
* *Configuration files*
* *Dockerfile*

* **Fill out the following section if you used data in your project** * 

**Data type:**

**Data size:** 
 
**Link to the data:**
