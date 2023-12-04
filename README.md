# Application-of-Customizing-embeddings-and-BM25

Leveraging NLP to Extract Insights from News
 
# 1.     Whole Introduction:
With growing interest in ESG investing, asset managers need to rapidly analyze news related to ESG topics to gain timely insights and make informed decisions. However, the unstructured nature of news articles makes quickly extracting relevant information difficult. This project aims to address this challenge by leveraging natural language processing to extract actionable insights from ESG news.
Specifically, this project will annotate and analyze Yahoo News articles related to environmental, social, and governance (ESG) topics. By developing fine-tuned NLP models using this dataset, we will retrieve relevant ESG articles, classify their sentiment, and identify causal relationships between ESG events and market impacts. This multi-pronged approach will generate actionable insights from unstructured ESG news to support data-driven investment decisions.

# 2.     Goals:
The goals of this project are to 
1) annotate ESG-related articles,
2) Enhance ADA2 accuracy while comparing BM25

   
# 3.     Project Plan:
Task 1: Annotation
·       Annotate more than 5,000+ articles related to Environmental, Social, and Governance (ESG) and SASB categories
·       Employ models like ChatGPT, Llama2 (or fine-tuned models such as Alpaca) to automatically label news articles and identify relevant entities 
Task 2: Evaluation and Fine-tuning of Retrieval Models - 3 
·       Use Classical Information Retrieval methods (like BM25)


# Customizing-embeddings
we provide a method for customizing your embeddings using training data. The idea of the method is to train a custom matrix to multiply embedding vectors by in order to get new customized embeddings. With good training data, this custom matrix will help emphasize the features relevant to your training labels. You can equivalently consider the matrix multiplication as (a) a modification of the embeddings or (b) a modification of the distance function used to measure the distances between embeddings. 

https://private-user-images.githubusercontent.com/101485360/280610496-8550b94c-8349-4731-94ec-85a514e3c983.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDE2NjE5MjYsIm5iZiI6MTcwMTY2MTYyNiwicGF0aCI6Ii8xMDE0ODUzNjAvMjgwNjEwNDk2LTg1NTBiOTRjLTgzNDktNDczMS05NGVjLTg1YTUxNGUzYzk4My5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIwNFQwMzQ3MDZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iOGY1MmJjOWVmYjk5NDQwYjc3YmQwMWM5MmM0YzM3NTg2NmRhYWI0YTk2MjIwZjgwMjBlYTA0YzZlNzUxNTNlJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.z2HzbClEJqRzaJmT3u36oMiACe0szfdeLVZ1dNY0vHI![image](https://github.com/ruiqiizhou/Application-of-Customizing-embeddings-and-BM25/assets/101485360/72b3444c-4ef6-4766-88ab-a810909a6c0e)



