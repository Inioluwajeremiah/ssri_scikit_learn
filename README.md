## Machine Learning Prediction of the bioactivity(Ki) of Serotonin Reuptake Inhibitors

Selective Serotonin Reuptake Inhibitors (SSRIs) are drugs used to treat mental diseases such as depression and anxiety disorders. They enhance neurotransmission and mood control by increasing serotonin levels in the brain.  using datasets from CHEMBL database, A machine learning algorithm-based model was built tpredict the inhibitory constant (Ki) values of SSRIs. Different machinelearning ensemble methods were used together with molecular fingerprints from PADeL descriptor. Decision Tree together with Klekotha-Roth Fingerprint performed best with 92% accuracy and hence identifying lead compounds that strongly bind to the target molecule (SERT). The model was then used to screen potential SSRIs from the ZINC database. This revealed promising compounds, like ZINC00427761, ZINC00427746, ZINC00425581, and ZINC00427764 which displayed strong binding affinities and interactions with SERT. The inhibitory mechanisms of these compounds against SSRIs were then analyzed using molecular docking simulation based on the structure-activity relationship between these candidates and the protein target, SERT. This study shows that our model can potentially screen bioactive compounds targeting SERT and offer the basis for further research into  databases with large chemical space that can potentially be utilized as a novel treatment for depression.

### Tools used
1. Scikit Learn
2. Padel Descriptors
3. Jupyter Notebook
4. RDKit


### Database
1. Chemble Database
2. Zinc Database

