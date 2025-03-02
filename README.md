# NLP
In the repo i will going to put all the resource related to nlp
### Text Transformation technique
1. one hot encoding
2. bag of word
3. word2vec
4. NGrams
5. TF-IDF
6. CBOW
7. AVGWORD2VEC
8. etc
#### many other techniques are also there in market if you search there are lots of there but i only put popular or most used ones which can be heandy as well


### TF-IDF -> Term Frequency - Inverse  Frequency

<h4>
  
TF-IDF stands for term frequency-inverse document frequency. It's a technique used to measure the importance of words in a document. It's a key tool in information retrieval and natural language processing (NLP). 
How it works 
- Term frequency (TF): The number of times a word appears in a document
- Document frequency (DF): The number of documents that contain the word
- Inverse document frequency (IDF): Weighs down common words and increases the weight of rare words
Why it's useful
- Search engines: TF-IDF is used to rank documents in search results 
- Machine learning: TF-IDF helps machine learning models read words 
- Text classification: TF-IDF is used to classify text 
History 
The concept of TF-IDF was introduced in the 1970s by Karen Spärck Jones and Stephen Robertson at the University of Cambridge
In Python 
**You can use the TfidfVectorizer() method in the sklearn module to compute TF-IDF values** 
  
</h4>

## Term Frequency (TF) Formula  
\[
TF(t) = \frac{f_t}{N}
\]  
where:  
- \( f_t \) = Number of times term \( t \) appears in the document  
- \( N \) = Total number of terms in the document  

## Inverse Document Frequency (IDF) Formula  
\[
IDF(t) = \log \left(\frac{N_d}{df_t} + 1\right)
\]  
where:  
- \( N_d \) = Total number of documents  
- \( df_t \) = Number of documents containing term \( t \)


