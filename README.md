## Prediction of Stroke Risk Factors for Better Pre-emptive Healthcare: A Public-Survey-Based Approach

 This repository contains the code for our <p><a href="https://doi.org/10.1007/978-981-15-6353-9_2">ICACIE 2019 paper </a></p>
 
 ```Debayan Banerjee and Jagannath Singh
 Prediction of Stroke Risk Factors for Better Pre-emptive Healthcare: A Public-Survey-Based Approach
 in ICACIE 2019
 ```

If you find the code useful for your research, please cite our paper:

```
Banerjee D., Singh J. (2021) Prediction of Stroke Risk Factors for Better Pre-emptive Healthcare: A Public-Survey-Based Approach. In: Panigrahi C.R., Pati B., Mohapatra P., Buyya R., Li KC. (eds) Progress in Advanced Computing and Intelligent Engineering. Advances in Intelligent Systems and Computing, vol 1199. Springer, Singapore. https://doi.org/10.1007/978-981-15-6353-9_2
```
for dataset details :
<a href="https://www.cdc.gov/brfss/annual_data/annual_data.htm">BRFSS </a>

for initial set-up : 
```
the given code was run on -
1. UBUNTU-16.04 with 4-CORE processor and 8 GB RAM
2. RStudio with R version 3.6.3
3. H2O library called from RStudio IDE
```
# Figure 1 : 

![Figure1](/images/Figure1.png)

<p><a href="feature_selection.rmd ">feature_selection.rmd </a></p>

# Figure 2 : 

![Figure2](/images/Figure2.png)

<p><a href="interFeature_correlation.rmd ">interFeature_correlation.rmd </a></p>

# Figure 4 : 

![Figure4](/images/Figure4.png)

<p><a href="featureTarget_correlation.rmd ">featureTarget_correlation.rmd </a></p>

# Figure 3 : 

![Figure3](/images/Figure3.png)

<p><a href="model_building.rmd ">model_building.rmd </a></p>

# Figure 5 :

![Figure5](/images/Figure5.png)

<p><a href="downsampledModel_building.rmd">downsampledModel_building.rmd </a></p>

# Figure 6 :

![Figure6](/images/Figure6.png)

<p><a href="downsampledModel_building.rmd">downsampledModel_building.rmd </a></p>

# Table 1 :

Index | BRFSS       |codes Meaning
1        |CVDSTRK3 | Ever told you had a stroke.
2 USENOW3 Usage of tobacco products other than cigars
3 SSBSUGR1 Intake of sugar sweetened beverages excluding diet soda or
diet pop over last 30 days
4 SSBFRUT1 Intake of sugar sweetened fruit drinks including fruit drinks
made at home with added sugar over last 30 days
5 X.SMOKER3 Four-level smoker status: Everyday, Someday, Former, Non-
smoker
6 X.TOTINDA Adults who reported doing physical activity or exercise dur-
ing the past 30 days other than their regular job
7 AVEDRNK2 Total number of occasions of alcohol drinking in last 30 days
8 FRUIT1 Excluding fruit juice, intake frequency of fruits over last 30
days
9 FRUITJU1 Frequency of 100% PURE fruit juices excluding fruit-
flavoured drinks with added sugar over past 30 days
10 FVBEANS Intake frequency of beans (all types) over last 30 days
11 FVGREEN Intake frequency of green-coloured vegetables (all types)
over last 30 days
12 FVORANG Intake frequency of orange-coloured vegetables (all types)
over last 30 days
13 VEGETAB1 Not counting 10, 11 and 12, intake frequency of vegetables
over last 30 days
14 SLEPTIME Average sleeping hours per day
15 SCNTWRK1 Average work hours per week
16 X.CHLDCNT Number of children in household (Categories: 0, 1, 2, 3, 4,

<p><a href="feature_selection.rmd ">feature_selection.rmd </a></p>

# Table 2&3 :

<p><a href="downsampledModel_building.rmd">downsampledModel_building.rmd </a></p>
