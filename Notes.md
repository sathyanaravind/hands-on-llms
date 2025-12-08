Topic Modelling

1. Embedding documents
2. Dimensionality Reduction
3. Clustering


assigning labels to clusters - topic modelling
- instead of using single word as lables here we use keywords
- traditional methods LDA uses bag of words to extract keywords but doesnot take into account context or meaning

modern 
BERTopic: a modular topic modelling framework
- leverages clusters of sematinc smiliar texts to extract various types of topic representations
￼
step 1 : form clusters
step 2: models a distribution over words in the vocabulory using bag of words 

however ther are 2 problems”
- this is a reprsntaion at docment level
- to address this TF-IDF
    - put more weights on words that are more meaningful to a cluster, put less weight on words that are used across 
￼
<img width="439" height="224" alt="image" src="https://github.com/user-attachments/assets/f24465f4-d146-4fd3-81b5-6f5b95b8735f" />
