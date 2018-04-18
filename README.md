> **If you use the resources (algorithm, code and dataset) presented in this repository, please cite our paper.**  
*The BibTeX entry is provided at the bottom of this page. 

# Your paper title
Human occupancy counting is crucial for both space utilisation and building energy optimisation. In the current article, we present a semi-supervised domain adaptation method for carbon dioxide - Human Occupancy Counter (DA-HOC), a robust way to estimate the number of people within in one room by using data from a carbon dioxide sensor. In our previous work, the proposed Seasonal Decomposition for Human Occupancy Counting (SD-HOC) model can accurately predict the number of individuals when the training and labelled data are adequately available. DA-HOC is able to predict the number of occupancy with minimal training data, as little as one-day data. DA-HOC accurately predicts indoor human occupancy for a large room using a model trained from a small room and adapted to the larger room. We evaluate DA-HOC with two baseline methods - support vector regression technique and SD-HOC model. The results demonstrate that DA-HOC's performance is better by 12.29% in comparison to SVR and 10.14% in comparison to SD-HOC.

This repository contains resources developed within the following paper:

Arief-Ang, I.B., Salim, F.D. and Hamilton, M., 2017. DA-HOC: Semi-supervised Domain Adaptation for Room Occupancy Prediction using CO<sub>2</sub> Sensor Data. Proceedings of the 4th ACM International Conference on Systems for Energy-Efficient Built Environments (BuildSys 2017), pp.1-10.
  
You can find the [paper](link_to_your_github_pdf_resource_file.pdf) and [presentation](link_to_your_github_pdf_resource_file.pdf) in this repository. 

Alternative link: https://dl.acm.org/citation.cfm?id=3137146

## Contents of the repository
This repository contains resources used and described in the paper.

The repository is structured as follows:
> **NOTE:** this should follow the folders you have in this repository 

- `algorithms/`: Formal description of algorithm for entity normalization and sentence clustering.
- `data/`: Dataset used for this paper. 
- `code/`: Evaluation script.
- `evaluation/`: Evaluation script.
- `presentation/`: PDF of paper presentation in certain conference or venue.

## Code
Brief explanation about your code (where to start or how to run). 

## Data
Brief explanation of your datasets. 

## Possible Applications

## Additional Section
Additional section. 

## Citation
If you use the resources (code and dataset) presented in this repository, please cite (using the following BibTeX entry):
```
@inproceedings{AriefAng2017DAHOC,
 author = {Arief-Ang, Irvan B. and Salim, Flora D. and Hamilton, Margaret},
 title = {DA-HOC: Semi-supervised Domain Adaptation for Room Occupancy Prediction Using CO2 Sensor Data},
 booktitle = {Proceedings of the 4th ACM International Conference on Systems for Energy-Efficient Built Environments},
 series = {BuildSys '17},
 year = {2017},
 isbn = {978-1-4503-5544-5},
 location = {Delft, Netherlands},
 pages = {1:1--1:10},
 articleno = {1},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/3137133.3137146},
 doi = {10.1145/3137133.3137146},
 acmid = {3137146},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {ambient sensing, building occupancy, contextual information, cross-space modeling, domain adaptation, number estimation, presence detection, transfer learning},
}
```
