# ADD PAPER TITLE HERE
ADD AUTHORS AND OTHER INFO HERE
This repository holds all the code and data for the paper [NAME OF PAPER]

## ADD ABSTRACT HERE

All the analysis is done in Python 3 and is written in ipython notebooks. The code is to be executed in the order indicated in the filename (1 -> 2 -> 3 etc). 

# Folder Structure

```
├── Data
│   ├── GeneName.csv: Table of gene names and symboles for all the genes tested and considered in this study.
│   ├── PPIs/: All data regarding the PPI datasets.
│   │   ├── Download/: Dowloaded DroID tabular screen files.
│   │   └── PPI_2018_08.graphml: Compiled PPI graph from all the DroID single screen datasets.
│   ├── Screen/: All data regarding the different measurements performed in the screens. If _pred in the name, this corresponds to the measurements done on the predicted connectors.
│   │   ├── Raw/: Raw datasets as csv files for the three screens.
│   ├── ScreenPPI_[Metric].csv: Tabular file reccording the calculated centrality metrics for each genes in the PPI.
│   ├── fbgn_annotation_ID_fb_2018_06.tsv.gz: Flybase annotation dump of at 06/2018.
│   └── signaling.csv: Table matching the genes in this study with the signaling pathway they participate in.
├── Notebooks/: Ipython notebook of all the scripts used in this study. 
└── Results:/ Folder containing all the results outputed by the scripts in the Notebooks folder.
    ├── Candidate_Above_Z_Threshold.csv: List of all the screen genes that passed the Z threshold.
    ├── ConnectorGeneList_2018_08.csv: List of all the predicted connectors.
    ├── Core_module_2018_08.graphml: Graph of the predicted core module.
    ├── EggL_module_2018_08.graphml: Graph of the predicted Egg Laying module.
    ├── Hpo_EggL_module_2018_08.graphml: Graph of the predicted HippoRNAi Egg Laying module.
    ├── Ova_module_2018_08.graphml: Graph of the predicted Ovariole number module.
    ├── Meta_module_2018_08.graphml: Graph of the Meta Module.
    ├── MasterTable.csv: Master Table summarizing all the key data generated in this study (Published as Table S1)
    ├── MetaNetworkData_2018_08.csv: Table data summarizing the meta module.
    ├── Modules_Table_2018_08.csv: Table summarizing the genes in each of the predicted modules.

```

