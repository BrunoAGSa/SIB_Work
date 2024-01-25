# SIB_Work

## Drug-Target Interaction Prediction

Determining how well a small-molecule drug binds to a new target protein typically involves screening various compounds to gauge their effectiveness. Traditional methods for this rely on costly and time-consuming high-throughput wet-lab experiments. Unfortunately, these methods struggle when handling a large number of candidate compounds due to their resource-intensive nature. To tackle this challenge, drug-target interaction (DTI) prediction tasks employ computational methods that work virtually, using available structural data of compounds and protein amino acid sequences. By doing so, these computational models aim to predict how well a drug interacts with a target protein without the need for expensive lab experiments. Using techniques like machine learning and molecular modeling, these models offer a cost-effective and efficient means to forecast potential drug-target interactions. This advancement in predictive modeling holds great potential for accelerating drug discovery by quickly identifying promising compounds for further experimental exploration, potentially saving time and resources in the early stages of drug development.

## Impact:
Machine learning models that can accurately predict affinities can not only save pharmaceutical research costs on reducing the amount of high-throughput screening, but also to enlarge the search space and avoid missing potential candidates.

## Generalization:
Models require extrapolation on unseen compounds, unseen proteins, and unseen compound-protein pairs. Models also are expected to have consistent performance across a diverse set of disease and target groups.


# KIBA Dataset

### Link: 
https://tdcommons.ai/multi_pred_tasks/dti/#kiba

The chosen dataset is KIBA, which fulfills the requirements of the task as it involves supervised machine learning in a regression model. It contains at least two types of input variables: protein sequences and chemical compounds (drugs).

KIBA provides information on the binding of kinase inhibitors to target proteins, used for predicting Compound-Protein Interactions. The KIBA (Kinase Inhibitor Bioactivity) dataset is a specialized dataset curated specifically for studying the interactions between kinase inhibitors and their target kinases. Kinases are a class of enzymes involved in cellular signaling pathways and are significant targets in drug discovery, particularly in cancer treatment and other diseases related to aberrant signaling pathways.Kinases are a class of enzymes involved in cellular signaling pathways and are significant targets in drug discovery, particularly in cancer treatment and other diseases related to aberrant signaling pathway.

## Dataset Description: 
Toward making use of the complementary information captured by the various bioactivity types, including IC50, K(i), and K(d), Tang et al. introduces a model-based integration approach, termed KIBA to generate an integrated drug-target bioactivity matrix.

## Task Description: 
Regression. Given the target amino acid sequence/compound SMILES string, predict their binding affinity.

## Dataset Statistics: 
0.3.2 Update: 117,657 DTI pairs, 2,068 drugs, 229 proteins. Before: 118,036 DTI pairs, 2,068 drugs, 229 proteins.

## References:

[1] Tang J, Szwajda A, Shakyawar S, et al. Making sense of large-scale kinase inhibitor bioactivity data sets: a comparative and integrative analysis. J Chem Inf Model. 2014;54(3):735-743.

[2] Huang, Kexin, et al. “DeepPurpose: a Deep Learning Library for Drug-Target Interaction Prediction” Bioinformatics.

