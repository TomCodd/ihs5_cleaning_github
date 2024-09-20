# ihs5_cleaning_github


## Introducing the Malawi’s IHS5 data cleaning process

Tang et al. (2021) and Adams et al. (2022) describe how to tidy, process, and transform HCES food consumption or acquisition data into usable metrics for estimating household-level apparent food consumption and micronutrient intake. We used the steps from Tang et al. and Adams et al. to analyse Malawi's IHS5 data.  This code repository was created to provide detailed instructions for cleaning and processing IHS5 data. The repository is divided into two sections. 

* `scripts` - Series of R scripts for IHS5 data processing<br>
* `data` - Complementary data relating to the scripts<br>

Below is a directory tree that outlines the structure of the repository:

```
├─ scripts/
│  ├─ 1_ihs5_cleaning/
│  ├─ 1B_ihs5_cleaning/
│  ├─ 2_ihs5_nsu_conversion/
│  ├─ 3_ihs5_outliers/
│  ├─ afeIHS5/
│  ├─ fctMatchFinal/
│  ├─ fgMatch/
│  └─ ...
├─ data/                              
│  ├─ fct_ihs5_vv2.1/
│  ├─ hme.final/
│  ├─ /
│  ├─ india/
│  ├─ ethiopia/
│  ├─ individual_level_india/
│  ├─ dietary_assessment/
│  └─ ...
