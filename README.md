# Harriet.ai

Welcome to Questions.ai, where Harriet the AI, uses Natural Language Processing to answer questions, given a query.

Harriet, a small sister to IBM's Watson, will perform two tasks: document retrieval and passage retrieval while having access to a corpus of text documents. When presented with a query (a question in English asked by the user), document retrieval will first identify which document(s) are most relevant to the query. Once the top documents are found, the top document(s) will be subdivided into passages (in this case, sentences) so that the most relevant passage to the question can be determined.

Harriet uses tf-idf to rank documents based both on term frequency for words in the query as well as inverse document frequency for words in the query. Once we’ve found the most relevant documents, there many possible metrics for scoring passages, but we’ll use a combination of inverse document frequency and a query term density measure.

# Demo
https://youtu.be/X42gm5pl298
