# Arabic Dialect Identification

This is a repository of Arabic Dialect Identification Bert Based Model

# About Arabic Dialect Identification Model
we introduced an enhanced method for Arabic language dialect identification. We investigated simple techniques such as logistic regression and recent advanced deep-
learning based classifiers. We achieved best performance using our finetuned BERT based model that provided 85.8% accuracy on 4 Classes (MSA, Egy, Glf and Lev) and 90.4% accuracy on 3 Classes (Egy, GLF And Lev). The model can be found on the following [link](https://drive.google.com/file/d/165CtKwqDvHBYGvRUU_NBY2cbKBsqeev2/view?usp=sharing)

# Usage
Make sure to download the model file and extract it in the main folder
after that you can use our inference notebook script to use the model [inference script](https://github.com/naderessam110/Arabic_Dialect_Identification/blob/main/inference.ipynb)

# Requirements
* pandas
* nltk
* pyarabic
* transformers
* tqdm
* numpy
* tensorflow
