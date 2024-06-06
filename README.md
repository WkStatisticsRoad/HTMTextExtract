This repository contains the benchmark dataset, geoscientific dataset names for training, and code for experiments in the field of geoscience. The main components are:

Geo-Terminology Relatedness Dataset (Geo-Terminology Relatedness Dataset.xlsx)

trainGeoscientificDatasetNames (trainGeoscientificDatasetNames.txt)

Geoscientific Dataset Names (trainDataSetTitles.txt)

Research Literature (TestText.txt)


# Datasets
Geo-Terminology Relatedness Dataset: A benchmark dataset in the geoscience field.

trainGeoscientificDatasetNames: The geoscientific dataset names are used for HTM model training.

Geoscientific Dataset Names: Contains 12,642 dataset names from the ChinaGEOSS Data Sharing Network and the National Earth System Science Data Center. The dataset names are segmented using the NLPIR tool.

Research Literature: Contains 100 randomly selected research articles published in the Journal of Geography from 2021 to 2023. The research data sections are identified and segmented using NLPIR tools.

# Environment Setup
# Software
IDE: IDEA

Java Version: JDK 1.8

# Configuration File
pom.xml: Ensure that all dependencies and configurations are properly set up.

# Related Platform
We conducted experiments using the open-source HTM framework on the Numenta Platform for Intelligent Computing (NuPIC) (https://github.com/numenta/htm.java).
