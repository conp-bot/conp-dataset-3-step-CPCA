This OSF page contains data and analysis code for the paper - Item-specific overlap between hallucinatory experiences and cognition in the general population: A three-step multivariate analysis of international multi-site data.

The paper is published and available open access [here](https://www.sciencedirect.com/science/article/pii/S0010945221003099).

The dataset used in this study is a subset of a large multisite dataset. The filtered dataset used in this paper can be found in data/multisite_dataset_filtered_anon.csv. 
The data contains measures from the following cognitive tasks:
1. Consonant-vowel dichotic listening (DL)
2. Matrix reasoning (MR)
3. Source memory task (SMT)
4. Backwards digit span (DS)
5. Auditory signal detection (SD) (lab data collection only)

The data for Cardiff Anomalous Perceptions Scale (CAPS) and Launay-Slade Hallucination Scale - Extended (LSHS-E) questionnaires can be found in data/CAPS_by_item.csv and data/LSHS_by_item.csv respectively. 

The full dataset used in the [original study](https://psyarxiv.com/4wbgc/) can be found [here](https://osf.io/eqy76/).

Some variables have been removed or edited to ensure full anonymization of participants: age has been binned into categories, and gender removed.

The main analysis script is called Main.m. It loads the data from the raw data files and performs the CPCA analyses with reliability tests. The codes for data analyses are found in lib/.
The script generates the figures and tables for the paper and are saved in /Results.

For any questions, please contact Abhijit Chinchani at abhijitchinchani[at]gmail.com