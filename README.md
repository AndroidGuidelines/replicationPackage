# Guidelines for Architecting Android Apps: A Mixed-Method Empirical Study
This repository is the companion for the study: 
> R. Verdecchia, I. Malavolta, P. Lago. _"Guidelines for Architecting Android Apps: A mixed-Method Empirical Study"_. *Proceedings of ICSA’19: 16th International Conference on Software Architecture, Hamburg, Germany, 25 March - 29 March, 2019 (ICSA’18)*, 10 pages.

It contains all the material required for replicating our study, including: (i) the research protocol followed, (ii) the entirety of the search and selection execution data, (iii) the raw data extracted from the data points, and (iv) the documentation of data analysis processes accompanied by the relative results.

## Content
The entirety of the data required for the verification and replication of the study are provided in three separate folders, namely:

* [WL_selection_process](https://github.com/AndroidGuidelines/replicationPackage/tree/master/replication_package/WL_selection_process) - White Literature (WL) search and selection execution data
* [GL_selection_process](https://github.com/AndroidGuidelines/replicationPackage/tree/master/replication_package/GL_selection_process) - Grey Literature (GL) search and selection execution data
* [Data_extraction_and_analysis](https://github.com/AndroidGuidelines/replicationPackage/tree/master/replication_package/Data_extraction_and_analysis) - Raw extracted data, data analysis execution data and relative results.

For further information on the content of the folder see the directory structure overview reported below.

Directory Structure Overview
---------------
This reposisory is structured as follows:

    replication_package
    .
    |
    ├── ResearchProtocol.pdf                                      Research protocol of the study
    | 
    ├── Data_extraction_and_analysis/                             Extraction and analysis data                           
    |   |
    │   ├── Data_extraction_and_analysis-CLEAN.csv                Analysis of "clean architecutre" practices data
    │   |
    |   ├── Data_extraction_and_analysis-GEN.csv                  Analysis of generic Android architecutral practices data
    |   |
    │   ├── Data_extraction_and_analysis-MVP.csv                  Analysis of MVP practices data 
    |   |
    │   ├── Data_extraction_and_analysis-MVVM.csv                 Analysis of MVVM practices data 
    |   |
    │   ├── Data_extraction_and_analysis-Raw.csv                  Raw extracted data
    |   |
    │   ├── Data_extraction_and_analysis-Tags.csv                 Tags adopted for the analysis process
    |   |
    │   └── Data_extraction_and_analysis-Themes.csv               Data of the initial analysis of architectural practices
    |
    |
    ├── GL_selection_process/                                     GL search and selection execution data
    |   |
    │   ├── GL_Selection_Process-Cohen_Kappa_Calculation.csv      Cohen's Kappa calculation data
    |   |
    │   ├── GL_Selection_Process-GL_Selection_Query.csv           GL query results and selection process data
    |   |
    │   ├── GL_Selection_Process-GL_Snowballing.csv               GL snowballing results and selection process data
    |   |
    │   ├── GL_Selection_Process-Cohen_Kappa_rep_data.csv         Replication data for Choen's Kappa calculation
    |   |
    │   └── GL_data_sources/                                      Raw sources of GL data points
    |  
    |
    └── WL_selection_process/                                     WL search and selection execution data
        |
        ├── WL_Selection_Process-Google_Scholar_query.csv         WL query results and selection process data 
        |
        └── WL_Selection_Process-Snowballing.csv                  WL snowballing results and selection process data
