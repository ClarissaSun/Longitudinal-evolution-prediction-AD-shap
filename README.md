# Prediction of Longitudinal Evolution in Alzheimer’s Disease and Driving Force Analysis with Shap

####  Project Status: [Active]

## General study goal:

+ Predict future ourcome measurements of subjects at-risk of ad enrolled in the ADNI study 

+ Use shapley value on each feature to measure the driving force of the prediction





## Detailed study design











### Data preparation


Data used in the preparation of this article were obtained from the [Alzheimer’s Disease Neuroimaging Initiative (ADNI) database](adni.loni.usc.edu).



The data we used from ADNI consists of: 

(1) CSF markers of amyloid-beta and tau deposition; 

(2) various imaging modalities such as magnetic resonance imaging (MRI), positron emission tomography (PET) using several tracers: Fluorodeoxyglucose (FDG, hypometabolism), AV45 (amyloid), AV1451 (tau)as well as diffusion tensor imaging (DTI); 

(3) cognitive assessments acquired in the presence of a clinical expert; 

(4) geneticinformation such as alipoprotein E4 (APOE4) status extractedfrom DNA samples; 

(5) general demographic information.

Extracted features from this data were merged together into a final spreadsheet and made available on the LONI ADNI website.


### Model construction


For every individual, month-by-month forecasts of three key biomarkers: 

(1) Classification model: clinical status which can be either cognitively normal (CN), mild cognitive impairment (MCI) or probable Alzheimer’s disease (AD); 

(2) Regression model: ADAS-Cog13 (ADAS13) score; 

(3) Regression model: ventricle volume (divided by intra-cranial volume). 

### Model evaluation


### Model analysis










## Needs of this project

- frontend developers
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- writeup/reporting
- etc. (be as specific as possible)

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages) create another "setup.md" file and link to it here*  

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Contributing DSWG Members

**Team Leads (Contacts) : [Full Name](https://github.com/[github handle])(@slackHandle)**

#### Other Members:

|Name     |  Slack Handle   | 
|---------|-----------------|
|[Full Name](https://github.com/[github handle])| @johnDoe        |
|[Full Name](https://github.com/[github handle]) |     @janeDoe    |

## Contact
* If you haven't joined the SF Brigade Slack, [you can do that here](http://c4sf.me/slack).  
* Our slack channel is `#datasci-projectname`
* Feel free to contact team leads with any questions or if you are interested in contributing!































![overview](Figure/tadpole_overview.png)
