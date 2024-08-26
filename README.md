# llm-webtext-classification
Utilizing &amp; Evaluating LLMs on Web-Scrapped data

Note that "innovative_firm_classification_LORA.ipynb" was done in google colab. If you want to import dataset from folder, run this command instead: 
df_path = 'datasets/web_text_innov020824.csv' 
data = pd.read_csv(df_path)

![alt text](https://github.com/jinkett99/llm-webtext-classification/blob/main/images/background.png?raw=true)

# Future work: 
1. Evaluate "classifier LLM" directly on summary text dataset.
2. Evaluate XGBoost & counterparts on word embeddings (Done)
3. Improve on classification metrics with process choices based on contextual understanding + research.
