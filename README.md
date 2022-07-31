<a href="https://github.com/ilariam9">
	<img src0="https://avatars.githubusercontent.com/u/95041197?s=400&u=97f6a4ba30c2c19673cad9d04e88e65242417cbf&v=4" "width="100px;" alt=""/>
	<br /><sub><b>Ilaria Monti</b></sub>
</a>
# Predicting pain rating from brain activity.

## personal background
<a href="https://github.com/ilariam9">
   <br /><sub><b>Ilaria Monti</b></sub>
</a>
Education :
  * PhD student in Kinesiology and Physical Activity Science at University of Montreal

# Project definition

## Background

Pain is a multi-dimensional experience involving the activation of sensory, limbic and prefrontal brain areas. Hypnosis is psychological tool able to modulate pain perception using verbal suggestions. In the present study, verbal suggestions were used to induce a state of hyperalgesia, to increase pain perception, and hypoalgesia, to reduce pain perception. Suggestions were given while subjects were in the MRI scanner in order to record brain related activity. Immediately after the suggestions, a series of noxious electrical stimuli were administered to assess pain-related responses.


The aim of this project was to predict pain intensity ratings from fMRI brain images.

**Personal goals**
* Apply machine learning to neuroimaging data :heavy_check_mark:
* Learn visualization tools :heavy_check_mark:
* Improve my coding skills :heavy_check_mark:

## Tools

For the completion of this project, I used the following tool: 
* **Jupyter Notebook** to write the code for the analysis
* Python modules: 
   * Pandas: to manipulate the excel with the pain ratings
   * Numpy: to manipulate arrays
   * Nibabel: to load the fMRI contrast images 
   * Scikit-learn: to process machine learning analysis
   * Nilearn: to visualize the fMRI data
* The python scripts and figures will be added to the **github** repository

# Data

The dataset comes from Desmartaux et al., 2021 and is access restricted. It includes 24 participants (13 women and 11 males) and mean age is 26.9. But I had to exclude one participant since no pain rating was present. Participants
completed a fMRI scanning session where they received hypnosis suggestions. Suggestions were divided in neutral, hypoalgesic and hyperalgesic suggestion.
After the verbal suggestions, a series of either 6 or 9 painful stimuli were administered.


![protocole_desmartaux2021](protocole_desmartaux2021.png)	
				     
In total, each participant received 72 electrical shocks. A part one participant that received 60 electrical shocks. 
Consequently, the final data set included 23 participants for a total of 1644 trials/shocks across all participants.
The excel with the pain ratings for each participants can be found here <br> [Hypnosis_Pain_ratings.xlsx] (https://github.com/brainhack-school2022/monti_project/blob/main/Hypnosis_Pain_ratings.xlsx). 

## Deliverables

* Jupyter notebook for the Machine learning pipeline
* Jupyter notebook for visualizing the data and the results
* MarkDown README.md containing information about the project
* Github repository providing the scripts, graphs, report and relevant information


# Results
## Overview

### Actual Deliverables
* <br>[ML_Project_Hypnosis.ipynb] (https://github.com/brainhack-school2022/monti_project/blob/main/ML_Project_Hypnosis.ipynb) : script with the machine learning algorithm. 
* The Jupyter notebook with the data visualization need to be add.
