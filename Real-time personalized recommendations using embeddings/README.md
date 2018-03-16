# Real-time personalized recommendations using embeddings

## Jakub Mačina [@dmacjam](https://github.com/dmacjam)

- [about](https://2018.pycon.sk/en/speakers/Ma%C4%8Dina.html)
- [slides](https://www.slideshare.net/dmacjam/realtime-personalized-recommendations-using-product-embeddings)

### Abstract 
Recommender systems are successfully used in several domains, e.g. product or movie recommendation. In e-commerce, the aim is to provide personalized suggestions to users for relevant items out of all products available.

In this talk, I will focus on item recommendation for anonymous users when no historical data about user is available (also referred as a cold-start problem) and challenges we have encountered. Firstly, I will dig deeper into similar item recommendation by NLP model comparing textual descriptions of items. This approach is based on word embeddings extracted from neural network models, such as word2vec or fasttext.

Finally, I will talk about how to apply the same idea of word embeddings to learn a representation of each product. With the product embedding representation, it is easy to calculate similarities between products in real-time. Moreover, we found out that product embeddings are able to capture style of a product, color, category or a price level.

All of the examples will be practical using data about restaurants reviews and fashion products. Open-source NLP library Gensim is used in code samples. Presentation will be supported by visualization of embeddings to get the idea behind. Everybody with any interest in machine learning is welcome. After the presentation, you will know how to compute relationship between pizza and pasta or how to capture a fashion style of a user.

### Bio
My name is Jakub Macina and I work as an AI Engineer at Exponea. I have MSc in Information Systems at Slovak University of Technology focusing on machine learning and information retrieval. My research background is in the field of recommendation with a publication at a premier conference on recommender systems ACM RecSys. I co-founded a back pain preventing student project Spine Hero, winner of the Brilliant Young Entrepreneurs 2015 and semifinalist of the Microsoft Imagine Cup. I am passionate about movement and open source software (Google Summer of Code 2017 student, contributor to discussion platform Discourse).

