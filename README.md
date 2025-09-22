# media-selectivity-undergrad-thesis

Code for **["Identifying and Analyzing Selectivity in News Media Coverage Through Hierarchical Topic Modeling: Israel-Palestine as a Case Study"](https://github.com/jwrampino/media-selectivity-undergrad-thesis/blob/main/Identifying%20and%20Analyzing%20Selectivity%20in%20News%20Media%20Coverage%20Through%20Hierarchical%20Topic%20Modeling%3A%20Israel-Palestine%20as%20a%20Case%20Study.pdf)**

## Abstract

This study utilizes a corpus of news articles to identify broad trends in media selectivity regarding coverage of Israel-Palestine. The corpus is sourced from Nexis Uni, encompassing 8,500 articles composed of 302,564 sentences from 287 major news outlets, spanning from October 6, 2023 to October 18, 2023. By leveraging BERTopic at the sentence level, the semantic and syntactic content of articles was clustered into specific hierarchical topic groups. These groups were then aggregated across source and region level to analyze selective trends in coverage. The significance of this research lies in its potential to expand data-driven media studies by studying selectivity through semantically-oriented hierarchical topic modeling as a more objective and informative lens of analyzing the media agenda. Much prior political communication research on news-media emphasized their studies as analyses of bias, sentiment, or discourse. This study analyzes selectivity in coverage, out of the conceptualization of media simultaneously as framers and gatekeepers. Focus on selectivity reorients operationalization towards objective patterns of inclusion and exclusion at multiple scales.

## Project Description

## Methods

## Repository Structure

## Usage

## Results & Key Findings

## Limitations

## Acknowledgments

This project relies on the following tools and libraries:
- [BERTopic](https://github.com/MaartenGr/BERTopic) (Grootendorst, 2022) for topic modeling  
- [HDBSCAN](https://hdbscan.readthedocs.io/) for clustering  
- [scikit-learn](https://scikit-learn.org/) (including PCA) for preprocessing and decomposition  
- [NumPy](https://numpy.org/) and [pandas](https://pandas.pydata.org/) for data handling  
- [Matplotlib](https://matplotlib.org/) for visualization
- [UMAP](https://umap-learn.readthedocs.io/) was tested for dimensionality reduction but replaced with PCA

## Citation

Rampino, Jacob William. *Identifying and Analyzing Selectivity in News Media Coverage Through Hierarchical Topic Modeling: Israel-Palestine as a Case Study.* April 29, 2025. https://purl.lib.fsu.edu/diginole/honors_thesis_submission-cb2ac21b-e4e4-46b1-9d39-3c2b4a7a0833

**Note:** The official archival copy is under embargo in Florida State University’s DigiNole repository until 2027. This GitHub project contains the code developed for the thesis.

## License

This work is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).  
You are free to share and adapt this material for non-commercial purposes, provided that appropriate credit is given.  

For the full license text, see [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).
