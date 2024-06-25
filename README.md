# Anomaly Detection in Network Traffic Using Random Forest

Welcome to the GitHub repository for the paper titled, _"Anomaly Detection in Network Traffic Using Random Forest: A Study on Complete vs Partial Flow Data"_. This repository contains all the Jupyter notebooks, scripts, and datasets used in our study, serving as a comprehensive resource for replicating and understanding the research findings.

## Repository Structure

The repository is organized into several files and a directory, each serving a specific purpose in the research process. A breakdown of the repository's structure is as follows:

### Notebooks

**1-RawDataPreprocess.ipynb** - Prepares and cleans the initial dataset for further analysis.
   
**2-PreliminaryMeasurement.ipynb** - Preliminary analysis to explore dataset characteristics. Supports Section III.C of the paper.
   
**3-ProduceCompleteFlows.ipynb** - Processes data to produce complete flow records. Supports Section III.D.
   
**4-1-ProduceNPacketFlows.ipynb** - Generates partial flows based on packet counts. Supports Section III.E.1.
   
**4-2-ProduceNDurationFlows.ipynb** - Generates partial flows based on duration. Supports Section III.E.2.
   
**5-1-LabelFirstNPacketFlows.ipynb** - Labels the first N packet dataset distributions. Supports Section IV.A.1.
   
**5-2-LabelFirstNDurationFlows.ipynb** - Labels the first N duration dataset distributions. Supports Section IV.B.1.
   
**6-1-BinaryCvsNPacketFlows.ipynb** - Compares binary classification performance for packet counts. Supports Section IV.A.2.
   
**6-2-MultiCvsNPacketFlows.ipynb** - Compares multi-class classification performance for packet counts. Supports Section IV.A.2.
   
**6-3-BinaryCvsNDurationFlows.ipynb** - Compares binary classification performance for duration-based flows. Supports Section IV.B.2.
    
**6-4-MultiCvsNDurationFlows.ipynb** - Compares multi-class classification performance for duration-based flows. Supports Section IV.B.2.
    
**7-1-PC-Binary+Multi-Plots.ipynb** - Prepares plots for packet count based evaluations. Helper notebook.
    
**7-2-FD-Binary+Multi-Plots.ipynb** - Prepares plots for flow duration based evaluations. Helper notebook.

### Scripts

**labeller.py** - Contains functions for the labeling mechanism as discussed in Section III.B.

### Datasets

**[datasets](datasets/)** - Contains all datasets created and used throughout the examination.

## Documentation

For a detailed understanding of the methodologies and insights derived from this project, we encourage you to refer to our research paper. The paper elaborates on the analytical methods employed and discusses the broader implications of our findings in the field of network security anomaly detection.

For further insights and a deeper exploration of our methodologies, the research paper provides a comprehensive source of information, enhancing both practical and theoretical understanding of the work presented in this repository.

