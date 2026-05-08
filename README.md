# ChAlPred: Prediction of Allergenicity of Chemical Compounds

**ChAlPred** is the first web-based tool developed for the prediction of the allergenic potential of chemical compounds.
It is designed to assist researchers in identifying chemical allergens and designing chemical analogs with desired allergenicity, addressing a significant gap in the field of allergy prediction which has historically focused on proteins and peptides.

**Web Server:** [https://webs.iiitd.edu.in/raghava/chalpred/](https://webs.iiitd.edu.in/raghava/chalpred/)


## Citation

Sharma, N., Patiyal, S., Dhall, A., Devi, N. L., & Raghava, G. P. S. (2021).
**ChAlPred: A web server for prediction of allergenicity of chemical compounds.** *Computers in Biology and Medicine*, 136, 104746.


[https://doi.org/10.1016/j.compbiomed.2021.104746](https://doi.org/10.1016/j.compbiomed.2021.104746) 

This dataset can also be found on Zenodo at 


## About this Work

Allergy is an abrupt immune system reaction that can occur upon exposure to allergens. While many methods exist to predict the allergenicity of proteins and peptides,
ChAlPred was developed specifically to predict the allergenic potential of small chemical molecules. This is crucial for drug discovery and safety assessments, as chemical allergens can cause significant adverse reactions.

* **Dataset:** The tool was developed using a dataset of **403 allergenic** and **1,074 non-allergenic** chemical compounds obtained from the IEDB database.


* **Methodology:** Molecular descriptors and fingerprints were computed using **PaDEL software** to develop various machine learning-based prediction models.


## Key Features

### 1. Robust Predictive Models

* **Multiple Algorithms:** Employs several machine learning techniques, including Random Forest, Support Vector Machine (SVM), and Extra Trees.


* **High Performance:** The best-performing model achieved a maximum **AUROC of 0.88** on an independent dataset, demonstrating its reliability in discriminating between allergens and non-allergens.



### 2. Analysis and Design Capabilities

* **Allergenicity Prediction:** Users can submit chemical structures to predict their potential to induce an allergic response.


* **Analog Design:** Facilitates the design of chemical analogs with specific desired allergenic properties.



### 3. Integrated Web-Bench

* **Molecular Descriptors:** Analysis based on a wide range of chemical descriptors and fingerprints.


* **User-Friendly Interface:** Provides easy-to-use modules for searching, browsing, and predicting chemical allergenicity.


## Applications

* **Drug Safety Assessment:** Screening FDA-approved drugs and new drug candidates for potential allergenic side effects.


* **Toxicology:** Evaluating the safety of chemicals used in various industries, including cosmetics and food additives.


* **Chemo-informatics:** Using chemical descriptors and fingerprints to understand the molecular basis of chemical-induced allergies.


## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.


## Support

The development of ChAlPred was supported by the **Department of Computational Biology at IIIT-Delhi**. Acknowledgments are also given to the researchers and data providers whose work contributed to the training datasets.
