# ExploreData
Data package for "Explore Data" group project of RaukR.

The datasets are in raw format, you will have to figure out how to parse them.
You can find the datasets from within R using:

```
system.file("extdata", "visby_ais.log", package="ExploreData", mustWork = T)
system.file("extdata", "visby_adsb.log", package="ExploreData", mustWork = T)
system.file("extdata", "chr22.1000g.vcf.tar.gz", package="ExploreData", mustWork = T)
system.file("extdata", "heart_attack_analysis_dataset.tar.gz", package="ExploreData", mustWork = T)
```

## Chr22.1000g.vcf

File downloaded from the IGSR https://www.internationalgenome.org/data FTP site.
Originally named ALL.chr22.phase3_shapeit2_mvncall_integrated_v5b.20130502.genotypes.vcf it is a VCF format file with population allele frequencies of variants on chromosome 22. For size purposes the file supplied in RaukR has been filtered to 20000 random variants across chromosome 22.
Data is from 2504 individuals. 

## Heart attack analysis dataset

### Source

The dataset of Rashik Rahman was obtained from Kaggle, which was distributed
with [CC0: Public Domain](<https://creativecommons.org/publicdomain/zero/1.0/>)
license.

https://www.kaggle.com/rashikrahmanpritom/heart-attack-analysis-prediction-dataset

### Description of variables

_copied from the link_

#### About this dataset

- Age : Age of the patient
- Sex : Sex of the patient
- exang: exercise induced angina (1 = yes; 0 = no)
- ca: number of major vessels (0-3)
- cp : Chest Pain type chest pain type
    * Value 1: typical angina
    * Value 2: atypical angina
    * Value 3: non-anginal pain
    * Value 4: asymptomatic
- trtbps : resting blood pressure (in mm Hg)
- chol : cholestoral in mg/dl fetched via BMI sensor
- fbs : (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
- rest_ecg : resting electrocardiographic results
    * Value 0: normal
    * Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    * Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach : maximum heart rate achieved
- target : 0= less chance of heart attack 1= more chance of heart attack
