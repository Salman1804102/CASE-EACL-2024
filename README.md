## EcomFraudEX: An Explainable Machine Learning Framework for Victim-Centric and Dual-Sided Fraud Incident Classification in E-Commerce

**Author:** Salman Farsi, and Mahfuzulhoq Chowdhury

**Paper:** [Paper in Journal Website](https://publications.eai.eu/index.php/sis/article/view/6789)

**Database:** [European Union Digitral Library](https://eudl.eu/doi/10.4108/eetsis.6789)

## Abstract

The popularity of e-commerce businesses and online shopping is experiencing rapid growth all around the world. Nowadays, people are more inclined to shop online than in the actual shops. Due to this advancement, fraudsters have set new traps to deceive consumers. Whether it is true that customers often become victims of fraud, it also happens that a fraud customer tries to deceive the seller and hassle the seller intentionally in several ways. To address these issues, an automated system is required so that fraud incidents can be classified. This will facilitate taking legal action and reporting to consumer rights authorities. Existing research on fraud detection and prevention didn't cover customer and seller-side fraud simultaneously. Besides, most of the work focused on fraud detection rather than post-fraud incident classification. To overcome these gaps, this research endeavor conducts a thorough online survey of customers and sellers to gather incident-specific victim data on fraud cases and it addresses the issue for both customer and seller. This paper proposes a machine learning (ML) based explainable fraud incident classification framework EcomFraudEX, that can efficiently classify these fraud incidents and analyze the reason behind each incident. This framework particularly focuses on proper feature selection techniques, hyper-parameter tuning of models, and exploring different ML and ensemble models. Ensemble majority voting schemes consisting of Random Forest (RF), XGBoost, and CatBoost achieved the highest F1-score of 96% with the Chi-Square feature selection technique in the customer complaint dataset and 98% with the RF feature selection technique in the seller complaint dataset. To explain the incident reasoning, Local Interpretable Model Agnostic Explanation (LIME) and Shapely Additive Explanation (SHAP) were further utilized. The proposed scheme achieved a 1.57% higher F1-score and 2.13% higher accuracy than previous works.

## Contribution

- This article developed a machine learningbased interpretable fraud incident classification framework, EcomFraudEX. To find the topperforming model, it explored different ML models with optimal hyper-parameter tuning and performed ensembles of them by leveraging efficient feature selection techniques.
- This study collected two start-ofthe-art datasets, one from customers and another from sellers covering various types of fraud cases. This will be valuable for the country’s law enforcement authority and understanding of the fraudulent pattern.
- This study also handled the issue of class imbalances in the dataset by allocating weights to each class. Besides, the dataset was annotated by three annotators and checked by an expert to ensure that the bias effect in the dataset is reduced. This indicates that the experimentation was able to successfully develop a more generalized system.
- This paper finally delineated the reasoning of the model’s prediction through explainable AI methods SHAP and LIME. It uncovered important aspects that indicate why and how the fraud cases occurred.

## Methodology

Figure 1 shows a schematic diagram of the methodology.

<img title="Visual Representation of The Methodology" src="Methodlogy high.drawio (1000).png" alt="">

Figure - 01: Visual Representation of The Methodolog

<img title="Dataset Preparation" src="datasetfraud high.drawio.png" alt="">

Figure - 02: Data Collection & Preparation Procedure

## Cite this work
If you find this repository helpful in your work please cite the following
```
@ARTICLE{10.4108/eetsis.6789,
    author={Salman Farsi and Mahfuzulhoq Chowdhury},
    title={EcomFraudEX: An Explainable Machine Learning Framework for Victim-Centric and Dual-Sided Fraud Incident Classification in E-Commerce},
    journal={EAI Endorsed Transactions on Scalable Information Systems},
    volume={12},
    number={2},
    publisher={EAI},
    journal_a={SIS},
    year={2025},
    month={4},
    keywords={Fraud Detection, Fraud Prevention, E-Commerce, Explainable AI, Ensemble Majority Voting, Survey Data, Feature Selection},
    doi={10.4108/eetsis.6789}
}

```
## Note
`If you find any anomaly or have any query/suggestion feel free to ping.`
