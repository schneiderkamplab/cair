# Sharing is CAIRing: Characterizing Principles and Assessing Properties of Universal Privacy Evaluation for Synthetic Tabular Data
The accompanying paper can be found on [Arxiv](https://arxiv.org/abs/2312.12216).

## Abstract
Data sharing is a necessity for innovative progress in many domains, especially in healthcare. However, the ability to share data is hindered by regulations protecting the privacy of natural persons. Synthetic tabular data provide a promising solution to address data sharing difficulties but does not inherently guarantee privacy. Still, there is a lack of agreement on appropriate methods for assessing the privacy-preserving capabilities of synthetic data, making it difficult to compare results across studies. To the best of our knowledge, this is the first work to identify properties that constitute good universal privacy evaluation metrics for synthetic tabular data. The goal of such metrics is to enable comparability across studies and to allow non-technical stakeholders to understand how privacy is protected.  
We identify four principles for the assessment of metrics: Comparability, Applicability, Interpretability, and Representativeness (CAIR). To quantify and rank the degree to which evaluation metrics conform to the CAIR principles, we design a rubric using a scale of 1-4. Each of the four properties is scored on four parameters, yielding 16 total dimensions. We study the applicability and usefulness of the CAIR principles and rubric by assessing a selection of metrics popular in other studies. The results provide granular insights into the strengths and weaknesses of existing metrics that not only rank the metrics but highlight areas of potential improvements. We expect that the CAIR principles will foster agreement among researchers and organizations on which universal privacy evaluation metrics are appropriate for synthetic tabular data.

## The CAIR Rubric
An interactive rubric is provided as an [Excel sheet](https://github.com/schneiderkamplab/cair/blob/86c961f593da8b7614877d42ffafe0befd81713a/CAIR%20Scoring%20Rubric.xlsx) that allows scoring privacy evaluation metrics according to the CAIR principles.

## Citation
```
@article{Hyrup2023,
   author = {Tobias Hyrup and Anton Danholt Lautrup and Arthur Zimek and Peter Schneider-Kamp},
   doi = {10.48550/arXiv.2312.12216},
   journal = {CoRR},
   month = {12},
   title = {Sharing is CAIRing: Characterizing Principles and Assessing Properties of Universal Privacy Evaluation for Synthetic Tabular Data},
   volume = {abs/2312.12216},
   url = {http://arxiv.org/abs/2312.12216},
   year = {2023},
}

```
