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

<img width="714" alt="280610496-8550b94c-8349-4731-94ec-85a514e3c983" src="https://github.com/ruiqiizhou/Application-of-Customizing-embeddings-and-BM25/assets/101485360/0d5209f2-128a-4c45-acf4-055506860223">

# Why Customizing embeddings

### 1. **Targeted Semantic Understanding**
- **Domain-Specific Semantic Capture**: Standard word embedding models may not effectively capture the subtle semantic nuances specific to ESG or SASB topics. Custom embeddings can more accurately reflect the linguistic characteristics of these fields, thereby improving the accuracy of analysis.
- **Better Context Capture**: The context in news reporting may differ from that in general corpora. Custom embeddings can adjust according to the specific context of news content, providing deeper semantic understanding.

### 2. **Enhanced Relevance Matching**
- **Increased Matching Accuracy**: When matching news content with SASB topics, custom embeddings can consider industry terminologies, professional vocabularies, and specific topic language usage, aiding in more accurate matching.
- **Flexible Feature Representation**: Custom embeddings can be flexibly adjusted according to project needs, such as by including or emphasizing specific types of linguistic features to optimize the matching between news and topics.

### 3. **Improved Model Generalization**
- **Strong Adaptability**: As news topics and discussions evolve, custom embeddings can be updated with the latest datasets to maintain their sensitivity and adaptability to current discussions.
- **Future-Oriented Model Updates**: As ESG and SASB topics develop, custom embeddings can be continuously fine-tuned and optimized to adapt to changes in industry trends.

### 4. **Enhanced Model Performance**
- **Noise Reduction**: Custom embeddings can reduce the impact of language features irrelevant to the project goals, helping to decrease noise and enhance model performance.
- **Optimized Computational Efficiency**: Compared to some complex deep learning models, embeddings optimized for specific tasks might have advantages in computational efficiency.

### 5. **Data-Driven Decision Support**
- **Provision of In-depth Insights**: Custom embeddings can reveal complex relationships between news content and ESG topics, supporting more data-driven decision-making.
- **Enhanced Interpretability of Results**: Compared to black-box models, custom embedding models might offer better interpretability in certain cases, which is crucial for understanding model outputs and conducting result analysis.

# How we use Customizing-embeddings and BM25? （code demo）
https://colab.research.google.com/drive/1FtiI7SAFvFJvIa2H72ZZFAst5feva-_K

# Critical Analysis

### Impact of the Project

Enhanced ESG Analysis: By accurately matching news content with SASB topics, your project plays a crucial role in deepening the understanding of how current events and corporate activities relate to ESG (Environmental, Social, and Governance) factors. This is increasingly important for investors, policymakers, and the public.
Informed Decision-Making: For organizations and investors focused on sustainability and social responsibility, your tool offers valuable insights. It helps in identifying trends, risks, and opportunities related to ESG themes, aiding in more informed decision-making.
Advancing NLP in Finance: The project pushes the boundaries of applying natural language processing (NLP) techniques in the financial sector, particularly in the rapidly evolving area of sustainable finance.
Data-Driven Journalism and Research: For journalists and researchers, this tool can be a valuable asset in uncovering and understanding the connections between current news and broader ESG issues.
Public Awareness and Education: By highlighting the relationship between current news and ESG themes, your project can also contribute to public awareness and education about sustainability and corporate responsibility.

###Next Steps

Refinement and Expansion of Data Sources: Expand the range of news sources and SASB topics to cover a more comprehensive spectrum of information. This can include integrating multilingual news sources for broader global coverage.
Algorithm Enhancement: Continue to refine the custom embedding and BM25 algorithms based on user feedback and evolving data patterns. Implement machine learning techniques to improve accuracy and efficiency.
User Interface Development: Develop a user-friendly interface for easier access and interaction with the tool, making it more accessible to a broader audience.
Integration with Other ESG Data: Combine the tool's outputs with other ESG data sources for a more holistic view of a company's or topic's ESG performance.
Collaboration and Partnerships: Partner with academic institutions, financial organizations, and sustainability-focused entities to enhance the tool's capabilities and reach.
Machine Learning Model Deployment: Explore deploying machine learning models to automate the identification and classification of ESG-relevant news content.
Feedback Loop and Continuous Improvement: Establish a feedback mechanism for users to contribute to the tool's improvement and accuracy, ensuring it remains relevant and effective.
By taking these steps, the projec

# Related resources from around the web
https://github.com/openai/openai-cookbook/blob/main/articles/related_resources.md

https://github.com/openai/openai-cookbook/blob/main/examples/Customizing_embeddings.ipynb

https://news.ycombinator.com/item?id=34904793

https://community.openai.com/t/customize-openai-embedding-model/224210


