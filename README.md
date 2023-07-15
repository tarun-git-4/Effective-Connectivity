# IIITA | MINI Project '23
# Analysis Of Effective Connecitivity Of Emotional State Using EEG Data

## Project Description
This study is aimed at determining how emotional state affects effective connectivity and controls brain areas and comparing the results for diﬀerent emotions. 

Project Objectives :-
* To demonstrate that the current mood, as measured by self-report, is a factor which affects the patterns of effective connectivity.
* Develop a directed network among brain channels, connected according to their causal relationship.
* Comparison of these networks among male or female subjects for various emotions.

## Datasets
### DEAP
"DEAP" stands for Database for Emotion Analysis using Physiological signals.

The DEAP dataset is a collection of physiological and electroencephalographic (EEG) signals recorded from participants while they watched music videos.

Download DEAP dataset from : https://www.eecs.qmul.ac.uk/mmv/datasets/deap/

### DENS
"DENS" stands for Dataset on emotion with Naturalistic Stimuli.

DENS dataset contains recordings of emotional reactions to both visual and cognitive tasks, such as working memory exercises, as well as emotional responses to emotional faces.

Download DENS dataset from : https://www.biorxiv.org/content/10.1101/2021.08.04.455041v2.full

## Methodology
We have created directed graphs between the channels or electrodes using granger causality test to visualize the connectivity and eventually calculated various statistical estimators like global efficiency, modularity, local efficiency, betweenness centrality,transitivity and many more to determine the small worldness and detect functional integration and segregation.

## Screenshots
### Brain Connectivty and Heatmap comparison among male and female subjects on the basis of one emotion
[![Screenshot-2023-07-16-025329.png](https://i.postimg.cc/MKH8Fpx1/Screenshot-2023-07-16-025329.png)](https://postimg.cc/dDbX7vh0)
### Graphs generated replicating channel interactions.
[![Screenshot-2023-07-16-025458.png](https://i.postimg.cc/nLbbrKm1/Screenshot-2023-07-16-025458.png)](https://postimg.cc/v4zSSV31)

## Tech Stack
* Python

* Networkx Library

* StatsModel

* Pandas

## Download the project
Execute: git clone https://github.com/tarun-git-4/Effective-Connectivity

## Author
Tarun Jayadevan
