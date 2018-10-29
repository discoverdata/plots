Project Title: 
Using machine-learning and open bioactivity data for developing prediction models to identify chemical inhibitors of an essential enzyme of the malrial parasite. 

Summary:
Malaria is a serious disease caused by Plasmodium falciparum (Pf) that could become fatal if the treatment is delayed beyond 24 hours after the onset of clinical symptoms. Recent reports suggest that Pf has been developing resistance to the widely available current drugs resulting in emergence of multi-drug resistant strains throughout the world. In view of this global epidemic there is an urgent need to discover novel compounds through fast and efficient approaches such as machine learning. For this project, open quantitative high-throughput screening (qHTS) data  available at PubChem (https://pubchem.ncbi.nlm.nih.gov) will be used to develop prediction models for chemical modulators of the malarial enzyme Plasmepsin, which is a subtype of Aspartic protease. It plays an important role in heomoglobin degradation and is essential for the survial of the parasite inside the human body. 

The dataset:
All the compounds were derived from 73 Plasmempsin bioassays. In the dataset a compound was labelled "Active" if it inhibited malarial Plasmepsin enzyme in a bioassay while "Inactive" if it did not inhibit or actively inhibit a similar human protein called Cathepsin D. Compounds which inhibit Cathepsin D protein are likely to case side-effects because upon ingestion they will end up binding Cathepsin D in addition to malarial Plasmepsin enzyme, therefore, I have decided to include them in my inactive dataset. This will however, make it significantly difficult for the model to identify compounds because the proteins bind similar kind of compounds. Final dataset composition is 328 actives and 430 inactives. 

Method:
Using various supervised machine learning methods (including support vector machine, random forest, neural network, k-nearest neighbors, and decision tree). The performance of the models was evaluated with an external data set containing bioactivity data submitted by ChEMBL and the NCATS Chemical Genomics Center (NCGC). This study showcases how open data in the public domain can be used to develop machine models for bioactivity prediction.

The dataset: 
The dataset I am using for the project, is derived from PubChem Bioassay database. 
