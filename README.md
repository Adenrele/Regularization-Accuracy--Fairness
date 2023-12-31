# Regularization, Accuracy and Fairness
Societal biases are present in arguably all instiutions including healthcare, education, finance and employment. For example, studies have shown that clinicians hold [racial biases in relation to pain perception in black patients](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4843483/) and this is reflected in treatment. Such biases influence data, analyses and resulting data products. 


Data bias can take the form of emerging definitions including: historical bias, represenatation bias, measurement bias, population bias and more.  Datasets biased in these ways can produce prejudicial algorithms as seen in a [Twitter’s consistent cropping of black people’s faces out of pictures](https://www.theguardian.com/technology/2020/sep/21/twitter-apologises-for-racist-image-cropping-algorithm). Method bias is a result of failure of rigourisity in model/algorithm production [including confirmation bias and correlation fallacy](https://link.springer.com/article/10.1007/s00146-021-01154-8). Algorithmic bias must be addressed to minimise adversarial impacts of data driven innovations. In the notebook and report present in this repository, the effect of regularization on the accuracy-fairness tradeoff for chosen datasets is explored and reported.

Note: Admittedly this notebook and report were completed in 2022 and require an update and code refinement.

## Key/Highlighted Methods Utilized
- Optimized pre-processing for bias mitigation
- Support Vector Machine
- Fairness metrics (statistical parity difference, error rate and error rate ratio)
