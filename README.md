# CIVE202_Spring2026_Group2_Project-4

## Project Overview 

This project was completed for the course Civil Engineering Analysis II at the University of Nebraska-Lincoln. 
The objective of the project was to evaluate potential bias in the FEMA National Risk Index methodology by conducting a sensitivity analysis and devloping an alternative definition of risk. 

The project involves:
  - The selection and anlysis using the Census Tract-level data for the these two states:
    Iowa and California. Selected specifically to provide a contrast between a predominantly
    rural state and a highly urbanzized state for a more meaningful comparison of risk
    distribution. 
  - Development of an alternate risk index using external research and datasets
  - Comparison of NRI resilts with the proposed model to identify potential categorial bias
  - Communicate findings through data visualization, summary tables, and geospatial mapping

The final output includes a scope of work (SOW), a formal document defining the tasks our group undertook to complete this project. Which identifies the two states we analyze in our risk analysis study, identifies at least two external resources that aided us in our analysis, reports the current NRI definitions of risk and explains how the current NRI is calculated using the NRI website links provided. A gantt chart providing a visual project schedule for each engineer. Raw & Clean data files. Python code file, a jupyter notebook documenting the code used to generate our solution, fully operational and executable without errors. As well as refrences. And a corresponding annotated code document (ACD) explaning said pyhton code and equations. Lastly, a written techinical report, containing a clear methodology for how we defined risk so the results are reproducible, written comoparison of our risk definitions and NRI's definitions. Taking in consideration of the ethical implications of risk definitions and examining what implications these differences will have on the poeple impacted by natrual disasters and how this relates to being able to give to communities FEMA funding in the future to migrate disasters. 

## Respository Structure 
The respository is organized as follows:

-`(RAW Files)`
 The raw data files used in the Python code file for each of our identified states at the Census Tract Level and rthe metadate from the NRI website.

-`(CLEAN Files)`
  The clean data files used in the Python code file for each of our identified states at the Census Tract Level and the metadate from the NRI website.
  
-`CIVE 202_Spring 2026_152-Group2_Project 4_Python Code.ipynb`
 Documents the code used to generate our solution.

-`ACD File`
 Includes a line-by-line explanation of code. 
 
-`GANTT CHART File`
 Contains Gantt Chart results. 

-`CIVE202_Spring2026_Group2_Project4_SOW.docx`
 Contains Scope of Work outlining project's goals and defines the tasks to conducting our risk analysis study.

-`CIVE 202_Spring 2026_Group 2_Project #4_Written Document.pdf`
   Contains detailed report on the background of the Risk Averse, LLC: Analysis of the Risk of Natural Disasters project. Summarizing the findings in the code that can be reused in the future. This report will contain: Scope of Work, Methodology to how we defined risk in our data analysis so results are reproducible, written comparison of our risk definitions to the NRI definitions. And results from our python code. 

-`READ.md`
 Documentation and user guide for this project. 

 ---

 ## Software and Requirements 

 This project was developed using:

 -Python
 -Required Libraries:
   - Numpy
   - Pandas
   - Seaborn
   - Matplotlib
   - Geopandas


## How to Run the Project (User Guide) 

### Step 1: Data Organization and Cleaning
1. Load raw NRI and SVI datasets into the notebook
2. Clean data by handling missing values 
3. Standardize column names and formats
4. Merge datasets using Census Tract FIPS codes

### Step 2: Research and Development
1. Review NRI methodology 
2. Replicate the NRI risk calculation logic
3. Develop an alternative risk definition using modified weighting or additional factors

### Step 3: Sensitivity Analysis and Comparison
1. Compute both NRI risk scores and alternative risk scores
2. Compare rankings and classifications
3. Identify differences that indicate potential categorical bias

### Step 4: Visualization and Mapping
1. Generate summary tables 
2. Create comparison plots 
3. Use GeoPandas to map Census Tract-level risk for each state

### Step 5: Interpretation and Report 
1. Interpret results in the context of risk distribution
2. Evaluate how different definitions impact communities
3. Discuss implications for policy, funding, and disaster mitigation


## Methodology
1. Data Collection and Integration
   
- NRI Census Tract-level data and CDC Social Vulnerability Index data were collected and merged using FIPS codes. Metadata files were used to interpret variable definitions and ensure consistency.

2. Data Cleaning and Preprocessing

- Missing and placeholder values (e.g., -999, -9999) were converted to NaN and handled appropriately. Variables were normalized where necessary to allow comparison across datasets.

3. Risk Model Development

- NRI Risk Model: Based on Expected Annual Loss (EAL), Social Vulnerability (SVI), and Community Resilience
- Alternative Risk Model: Developed by adjusting weights of key variables and emphasizing social vulnerability impacts

4. Sensitivity Analysis
  
- Both models were compared by evaluating differences in percentile rankings and categorical classifications. This allowed identification of potential bias in how risk is assigned across regions.


</> 

## Results Summary

- The alternative risk model produced noticeable shifts in risk rankings, particularly in areas with high social vulnerability
- Urban regions (California) tended to show higher variability in risk depending on the model used
- Rural regions (Iowa) showed more stable risk classifications across models
Differences between models highlight how weighting choices can significantly influence perceived risk

Summary tables and visualizations demonstrate:
- Distribution of risk scores across states
- Comparison of mean and maximum risk values
- Spatial variation in risk using geospatial mapping



## Conclusion
This project demonstrates that risk classification is highly sensitive to how risk is defined and calculated. The comparison between the NRI methodology and the alternative model reveals that:
- Risk is not purely objective and can be influenced by model assumptions
- Social vulnerability plays a critical role in shaping risk outcomes
- Different definitions of risk can lead to different policy and funding decisions

Understanding these differences is essential for ensuring fair and effective allocation of resources for disaster mitigation. Future work could expand this analysis to additional states and incorporate more refined weighting strategies.

 

Group 5
- Riley Ibero
- Remy Balderas
- Carter Janssen
- Trey Williamson

Civil Engineering 202
University of Nebraska-Lincoln
Spring 2026

