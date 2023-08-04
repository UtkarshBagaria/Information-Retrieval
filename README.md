# Information-Retrieval
Working on the 800,000 news files dataset, an information retrieval system. 
Among the thousands of files obtaining information is a very tedious task if one has to go through each and every word from every file.
This can be solved using an efficient information retrieval system.
Using several techniques like removing stop words, punctuations, lower case and stemming the data was first pre-processed and cleaned for use.

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/d408813c-cc55-402f-9885-a6d4a6d49d50)


A posting index was created on this data. With the word being the key which maps to a list. The first element of the list being the count of the word, second being another dictionary with each file it occurs in as the key with the word positions in the file as the values.

Using this posting index created, boolean retrieval was performed on the data.

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/539d2b1e-296e-4883-a1e7-ab0d21fe531b)


Positional retrieval was performed.

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/c0af7c39-9368-45c1-80ce-e549e23fbd9d)


Wild cary query.

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/7a14f093-1684-46a9-ad1c-1cf846cd16fd)
![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/39af64bd-4d5a-4be7-8351-c3602c9f219f)


Using the posting index created before a bi-word index was made and used for bi word query retrieval.

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/5690d400-e672-433b-8f5c-8e7160e0de12)


Retrieval using Similarity Index with Vector Space Model

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/678f79d1-68a2-4314-b825-7fe5a93933d0)


Likelihood Model using Bayes theorem

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/2081c8ca-c987-4de6-ad94-54ae10b4c9a6)


Assigned tf-idf scores based on the input.

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/9d704240-14a4-423f-b763-3a347df10248)


Obtained 0.9735667696532784 (97.35%) precision.

Relevance Feedback and reranking of results.

![image](https://github.com/UtkarshBagaria/Information-Retrieval/assets/79400700/c05bf45a-fe4a-4c95-8a6c-443ee8d95298)


