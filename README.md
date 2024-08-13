# Master Thesis: Seeing like a bee: approaching bee diversity and flower cover estimation by UV drone images

The present repository contains the codes used for my Master Thesis project.

Here is the abstract of the work:
Globally, biodiversity faces a decline attributed to anthropogenic caused phenomena such as climate change, habitat fragmentation, and intensified agricultural practices. 
This decline extends to essential crop pollinators, such as bees, whose abundance and diversity are diminishing. This poses a significant risk to numerous plant species relying on their vital pollination services too. 
Evaluating the status of bee populations is crucial for their conservation. Traditional field data collection methods are often costly and time-consuming, necessitating the development of alternative approaches for more affordable, 
rapid, and landscape-scale detection. Recently, remote sensing technologies, particularly unmanned aerial vehicles (UAVs), have been explored to address gaps in bee monitoring.

In this study, we expanded the capabilities of UAV monitoring by investigating the efficacy of ultraviolet (UV) images for evaluating bee diversity and abundance across nine agricultural meadows in the Southeast of the Netherlands. 
To achieve this, extensive field data on flower and bee diversity and abundance were gathered during a campaign in April 2022. Simultaneously, UV images were captured by UAV over the same fields and on the same days, which were 
subsequently processed into orthomosaics. Utilizing four machine learning methods—random forest, k-nearest neighbor, support vector machine, and neural network—we aimed to estimate the flower cover as depicted in the UV UAV images.

The derived estimates were subsequently compared to the in situ measured flower cover, bee abundance, and diversity to evaluate the efficacy of the UV UAV approach in estimating these variables.
Machine learning-based field cover classification demonstrated significant accuracy across all proposed algorithms, with the Random Forest (RF) and K-Nearest Neighbor (KNN) models emerging as the top performers.
In terms of regression results, a positive relationship was observed between flower cover estimated from UAV images and in situ measured bee abundance data, yielding R² values of 0.58 for the RF model and 0.55 for the KNN model. 
Correlations between UAV-estimated flower cover and in situ flower cover and bee species richness also indicated positive trends, though the results were not statistically significant. 
This suggests the need for additional attempts and larger sample sizes to draw more conclusive findings.

Overall, our findings affirm the viability of the proposed approach, integrating UAV technology and machine learning, for evaluating flower cover and bee abundance and diversity. 
This method has the potential to evolve into a valuable tool for large-scale, standardized, and cost-effective assessments of flower cover and the quality of bee habitats. 
Additionally, the inclusion of the UV spectrum among the remote sensing tools for monitoring bees and their habitat quality demonstrates promising enhancements in the field of bee conservation.
