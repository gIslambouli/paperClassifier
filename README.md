# paperClassifier
This repository produces two machine learning models trained to categorize quantitative academic text into one of the eight overarching categories on the [arXiv](https://www.arxiv.org). Both models are trained on the words coming from the title and abstract of about 120,000 papers uploaded to the arXiv. The initial data for this project was prepared by the arXiv organization and is freely available on [Kaggle](https://www.kaggle.com/datasets/Cornell-University/arxiv). The preprocessing of this data is carried out in the `preprocessData.ipynb` notebook.  The first model, contained in `MNBQuantitativeClassifier.ipynb` is a multinomial naive Bayes model, and the second model, contained in the `XGBQuantitativeClassifier.ipynb` is an XGBoost model. Both notebooks output a tuned model into the Models folder.  These achieve about an 80% accuracy on classifying text into one of the eight categories.
