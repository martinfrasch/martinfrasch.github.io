# martinfrasch.github.io
My GitHub Pages

# Predicting maternal morbidity considering the impact of ethnicity and socioeconomic status: focus on rehospitalization and postpartum depression.

To obtain the dataset, go to https://dash.nichd.nih.gov/.

Introduction

The advent of machine learning (ML) in medicine has opened opportunities for harnessing the power of ML to predict patient outcomes based on various data contained in the electronic medical records (EMRs) such as patient’s demographics, basic health and physiological characteristics.(Rajkomar et al. 2018; Lin et al. 2020) The exciting opportunity here is that taken by themselves such singular features do not tell a clearly predictive story, but combined in a ML modeling framework such so-called “weak learners” have the power to amount to highly predictive models of health outcomes.

This information-rich dataset allowed me to tackle two important aspects of the health outcomes:

1) Hypothesis 1: Demographic and socioeconomic characteristics influence the outcomes of being readmitted to the hospital (rehospitalization). 
2) Hypothesis 2: Demographic and socioeconomic characteristics along with psychiatric history influence the outcome of experiencing postpartum depression.

Methods

I set up a coding notebook environment in R Studio, a freely available open source environment, that efficiently ingests the nuMoM2b dataset as the input. The choice of software is optimized to run on regular desktop computers, thus requiring no special computing resources. This should help with wide utilization of the presented data science approach to this dataset to test other hypotheses.  

All steps in the notebook can be easily reproduced, step by step, on the existing data or the ML models can be updated/retrained as the new data come in. 
I summarize the key findings in the notebook as they are generated and in the manuscript (arXiv TBA).

I hope this approach will empower future researchers, even with limited or no data science background, to reproduce and enhance the presented results and approaches and generate further insights into which factors modify the maternal morbidity and mortality.

Results

The easiest way to view the results is by opening open the following HTML files: 
1) Hypothesis 1: maternal_nu_data.nb.html
2) Hypothesis 2: maternal_depression_data.nb.html

I supplied the salient output graphics as PNG or PDF files along with the underlying code as Rmd files. Those can be executed in R to validate and develop this further.

Please see the PDF "Supplemental Materials" for a summary of the project. 

References
Lin, Wei-Chun, Jimmy S. Chen, Michael F. Chiang, and Michelle R. Hribar. 2020. “Applications of Artificial Intelligence to Electronic Health Record Data in Ophthalmology.” Translational Vision Science & Technology 9 (2): 13.
Rajkomar, Alvin, Eyal Oren, Kai Chen, Andrew M. Dai, Nissan Hajaj, Michaela Hardt, Peter J. Liu, et al. 2018. “Scalable and Accurate Deep Learning with Electronic Health Records.” NPJ Digital Medicine 1 (May): 18.

Credit for the  for decision tree viz code goes to
http://rstudio-pubs-static.s3.amazonaws.com/463653_b50579f05ae246a9bfa4251ef9aae26b.html
