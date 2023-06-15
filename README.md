# Master Thesis - Bridging the Gap: An NLP-based Approach to Compare CSR Reports and News Coverage and Identify Greenwashing
This repository contains all the code for my MScBA Business Analytics & Management thesis (as of now unpublished). A link will be added once the thesis has been added to the Erasmus University Thesis Repository. 

Under the `data_collection_pre-processing` folder, you will find the code used to gather news data from Google News using the GNews package and the pre-processing of the sustainability reports and additional NexisUni articles (with most of the code for the PDF pre-processing being re-used from https://github.com/llbtl/paper_ssm01).
Under the `analysis` folder, you will find the code used for topic modelling and calculation of the greenwashing scores using various NLP techniques. 

## Abstract
This study aims to explore how NLP techniques can be used to quantify greenwashing. To achieve this, we make use of a conceptual discrepancy framework proposed in a previous study to define greenwashing as the measure of discrepancy between a company's symbolic actions and its substantive actions. As a new contribution to theory, we derive the symbolic actions from a company's sustainability report text and substantive actions from its news coverage text. Additionally, compared to previous studies, this paper proposes a new way to measuring such discrepancy through the use of NLP techniques, namely text similarity, sentiment analysis and claim verification. Each of the techniques is applied at a firm and topic level to develop a total of six scores. We then compare their performance by conducting a correlation analysis between each of the scores and a greenwashing measure constructed using data from the Refinitiv ESG database. We find that the sentiment analysis based firm-level score is the only developed measure that has a positive significant correlation with the Refinitiv derived index. Initial exploratory analysis also indicates that the performance of our measure changes based on the amount of news coverage a company receives and the sector it belongs to. 

