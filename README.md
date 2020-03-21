# Leveraging digital media data for pharmacovigilance
A social network based pharmacovigilance.

This repository contains the dataset used in our paper titled **"Leveraging digital media data for pharmacovigilance"** that is submitted at **"AMIA 2020 Annual Symposium"**.

## Files details

### Data/Common_known_sideeffects_found/:

This folder contain common known side effects found from twitter other reporting systems (FAERS, MedEffect and Drugs.com) for 11 different Drugs (Alprazolam, Adderall, Fluoxetine, Venlafaxine, Adalimumab, Lamotrigine, Quetiapine, Trazodone, Paroxetine, Metronidazole and Miconazole). There is a separate file for each drug and the columns are:
- drugname_drugsCom: Tanimoto coefficient scores of side effects found from Drugs.com.
- drugname_MedEffect: Tanimoto coefficient scores of side effects found from MedEffect.
- drugname_OpenFDA: Tanimoto coefficient scores of side effects found from FAERS.
- drugname_Twitter: Tanimoto coefficient scores of side effects found from Twitter.
- sideefects: Grouped ADRs used used for calculating tanimoto coefficient scores of a given side effects.
- known_sideeffect_medlineplus_drugs_com_webmd: known side effect found from the lists of known side effects from MedlinePlus, Drugs.com and WebMD.

### Data/Common_unknown_sideeffects_found/:

This folder contain common unknown side effects found from twitter other reporting systems (FAERS, MedEffect and Drugs.com) for 11 different Drugs (Alprazolam, Adderall, Fluoxetine, Venlafaxine, Adalimumab, Lamotrigine, Quetiapine, Trazodone, Paroxetine, Metronidazole and Miconazole). There is a separate file for each drug and the columns are:
- drugname_drugsCom: Tanimoto coefficient scores of side effects found from Drugs.com.
- drugname_MedEffect: Tanimoto coefficient scores of side effects found from MedEffect.
- drugname_OpenFDA: Tanimoto coefficient scores of side effects found from FAERS.
- drugname_Twitter: Tanimoto coefficient scores of side effects found from Twitter.
- sideefects: Grouped ADRs used used for calculating tanimoto coefficient scores of a given side effects.


### Data/side_effect_clusters/Avg_of_min_distance_average_21550_clusters.tsv:

Grouped ADR constructed by “Average min distance Average” as a clustering algorithm with k=21, 550 (number of clusters).

### Data/FDA_CHV_and_MedEffect_sideeffectlist.csv:

A list of 34, 392 unique groups, that was further clustered using “Average min distance Average”.


### Data/side_effect_lexicon.txt:
It contain the side effect lexicon used in this study. Each line consist of all the keywords that represent the same side effect and are grouped together.





