<center>

</h3> Example Project</h3>

<h1> Apple AppStore Apps</h1>

<strong>Preference Predictor</strong>

</center>
<br/>

<h2>Problem Statement</h2>
<br>

<h2>Documents</h2>
Notebooks and Documents are structured thinking about their functional scope:

- **ETL Notebooks**
  - A001 | Dataset Explorations, first observations (basic EDA) and Data understanding
  - A002 | Data Sanitizitacion: Outliers and nulls; data imputation, censored data asumption, other cleaning techniques
  - A003 | Feature engineering
  - A004 | Univariate and bivariate data analysis
- **Regressor Notebooks**
  - B001 | Early Options Perspective for Available Techniques
    - Lazy Predict
  - B002 | Regressors Construction and determination of components
    - ELI5, LIME, SHAP, Yellowbrick, Alibi, Lucid
  - B003 | Evaluation of regressor: Train, Test and Bootstraping
    - r2, Adjusted R2, RMSE and their stability of results
- **Reports PDFs**
  - Problem Statement
  - Results Evaluation
  - Problem Presentation

### Other Files:


| file | description |
|-----|-----|
| ./data/appleAppData.json | Raw Data |
| ./data/CleanedData.csv | Cleaned Data |
| ./data/TransformedVars.csv | Feature engineering Data |
| ./data/TestData.csv | Testing Data |
| ./data/TrainData.csv | Training Data |
| ./data/SynData.csv | Bootstraping Data |

### Acknowledgements

```
I couldn't have build this project without the:

  - The gift of learn for free:
      OPEN.ED@PSU, Baja Analytics, MIT OpenCourseWare, geeks for geeks, statweb @Rutgers,
      Google, Analytics vidhya, IBM, The Stats Geek, statisticsbyjim, Coursera and
      a lot more people and teams... Tnx 
      
  - inspiration: Vik Paruchuri @Dataquest
  
  - dataset: @gauthamp10
  
  - Platform: Github
  
  - Software: Jupyter and python
```

### __Notes__  
- The notebooks were worked on a PC win 10, 16 ram and in a
- Bootstrapping a regression model for model evaluation:
  - It is useful to know how much random variation there is in regression coefficients simply because of small changes in data values.
  
### __Author__

 **David Ochoa Corrales**

### __License__  

This project is licensed under the  License - see the THE CREATIVE COMMONS ATTRIBUTION 4.0 INTERNATIONAL [LICENSE](LICENSE.md) file for details
