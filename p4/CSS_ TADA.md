# Computational Social Science: Text Analyses

**Course Title:** Text As Data: Computational Methods in Social Science  
**Level:** Graduate / Advanced Undergraduate  
**Prerequisites:** Basic programming (Python or R), introductory statistics, interest in social science research  
**Tools:** 
- Python (NLTK, scikit-learn, gensim, spaCy)
- R (quanteda, tidytext)  

---

## From Text to Data

---

### Session 1: Text and Its Features
---

#### Features of Text
- **Text Metadata**
  - Author  
  - Date  
  - Type of text (e.g., news article, tweet, speech)  

- **Textual Features**
  - Length  
  - Sentence count, average sentence length  
  - Paragraph structure  

- **Complexity / Readability**
  - Lexical diversity (e.g., type-token ratio)  
  - Readability indices (e.g., Flesch-Kincaid, Gunning Fog)  
  - Syntactic structures and variation  

#### Content of Text
- **Tokenization**
  - Word and sentence tokenization  

- **Stop Words**
  - Standard lists  
  - Domain-specific customization  

- **Stemming / Lemmatization**
  - Rule-based vs. dictionary-based approaches  
  - Use cases and consequences  

---

### Session 2: Bag of Words
---

- **Bag of Words (BoW) Model**
  - Concept and construction of document-term matrices (DTM)  
  - Frequency-based representations  

- **TF-IDF (Term Frequency–Inverse Document Frequency)**
  - Intuition and application  
  - Use cases in social science texts  

  **Dictionary Approach**
  - How to use dictionary approach 
  - Strengths and Limitations of Sparse Representations 
      - Loss of context  
      - Dimensionality explosion
      - Sparcity of data 
      - Difficulty with Synonymy and Polysemy 
      - Computational efficiency  

---

### Session 3: Distributed Representations (Word Embedding
---

- **Vector Space Model Intuition**
  - Semantic similarity  
  - Analogies  


- **Word Embedding Models**
  - Word2Vec  
  - GloVe  
  - Contextual embeddings (e.g., BERT)  



- **Visualizing Embeddings**
  - Dimensionality reduction (PCA, t-SNE)  
  - Cluster analysis of semantic fields  

---

## How to Analyse the Data

---

### Session 4: Supervised Learning
---

- **Text Classification**
  - Training document

- **Text Scaling**
  - Wordscore
- **Common Machine Learning Models**
  - Naive Bayes  
  - Support Vector Machines (SVMs)  
  - Logistic Regression  
  - Random Forests  

- **Evaluation Metrics**
  - Accuracy  
  - Precision / Recall  
  - F1 Score  

- **Document Similarity**
  - Cosine similarity  
  - Use in recommendation or clustering tasks  

---

### Session 5: Unsupervised Learning
---

- **Text Classification (Structural Topic Modelling)**
  - Latent Dirichlet Allocation (LDA)  
  - Non-negative Matrix Factorization (NMF) 


- **Text Scaling**
  - Wordfish
  - Wordshoal
  
 
- **Dimensionality Reduction**
  - PCA, t-SNE for interpretation  
  - Use in pre-processing for clustering  

- **Unsupervised Learning in Social Science**
  - When and why to use unsupervised models  
  - Exploratory vs. predictive modeling  


---
### Session 6: Working with spaCy in python and R 
---

- **Basic Structure of spaCy**
  - Event sequences  
  - Dramatic tension curves (e.g., Freytag's pyramid)  

- **Name Entity Recognition**
  - Named entity recognition  
  - Frame detection and valence analysis  

- **Grammar-Based Parsing (Basic)**
  - Dependency parsing  
  - Sentence role identification (subject, object, action)  

- **Applications**
  - Political discourse analysis  
  - Media studies and framing  
  - Historical narratives and public opinion  

---

### Session 7: Narrative Detection
---

- **Narrative Arcs and Structure**
  - Event sequences  
  - Dramatic tension curves (e.g., Freytag's pyramid)  

- **Event and Framing Analysis**
  - Named entity recognition  
  - Frame detection and valence analysis  

- **Grammar-Based Parsing (Basic)**
  - Dependency parsing  
  - Sentence role identification (subject, object, action)  

- **Applications**
  - Political discourse analysis  
  - Media studies and framing  
  - Historical narratives and public opinion  

