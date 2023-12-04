# Application-of-Customizing-embeddings-and-BM25

Leveraging NLP to Extract Insights from News
 
# 1.     Introduction:
With growing interest in ESG investing, asset managers need to rapidly analyze news related to ESG topics to gain timely insights and make informed decisions. However, the unstructured nature of news articles makes quickly extracting relevant information difficult. This project aims to address this challenge by leveraging natural language processing to extract actionable insights from ESG news.
Specifically, this project will annotate and analyze Yahoo News articles related to environmental, social, and governance (ESG) topics. By developing fine-tuned NLP models using this dataset, we will retrieve relevant ESG articles, classify their sentiment, and identify causal relationships between ESG events and market impacts. This multi-pronged approach will generate actionable insights from unstructured ESG news to support data-driven investment decisions.

# 2.     Goals:
The goals of this project are to 
1) annotate over 5,000 ESG-related articles,
2) evaluate and fine-tune neural information retrieval models, 
3) perform supervised sentiment analysis using transformer models, and 
4) conduct causal analysis to determine the relationship between negative ESG news and public company returns.
   
# 3.     Project Plan:
Task 1: Annotation
·       Annotate more than 5,000+ articles related to Environmental, Social, and Governance (ESG) and SASB categories
·       Employ models like ChatGPT, Llama2 (or fine-tuned models such as Alpaca) to automatically label news articles and identify relevant entities
Task 2: Evaluation and Fine-tuning of Retrieval Models - 3 
·       Use Classical Information Retrieval methods (like BM25 and SBERT)
·       Contrast various Deep Neural Network models, such as the Two Towers model, All-to-all Interaction with BERT, and Late Interaction using ColBERT, etc. 
·       Explore strategies for fine-tuning these Retrieval Models and develop Mixed Retrieval Strategies.
