<div align="right">
<img src="https://user-images.githubusercontent.com/41562231/141720820-090897f9-f564-45e2-9265-15c1269db795.png" height="120" width="900">
</div> 

<small> <center>

[▸LinkedIn](https://www.linkedin.com/in/kunalkolhe3/) <a href="https://www.linkedin.com/in/kunalkolhe3/" target="blank"><img src="https://img.icons8.com/fluency/48/000000/linkedin.png" alt="Kunal K" height="20" width="20"/></a> ║ [▸Portfolio](https://kunalk3.github.io/Portfolio-Website-Kunalk3/) <a href="https://kunalk3.github.io/Portfolio-Website-Kunalk3/" target="blank"><img src="https://img.icons8.com/color/48/cloud-checked.png" alt="Kunal K" height="22" width="22"/></a> ║ [▸GitHub](https://github.com/kunalk3/) <a href="https://github.com/kunalk3/" target="blank"><img src="https://img.icons8.com/ios-filled/50/github.png" alt="Kunal K" height="18" width="18"/></a> ║ [▸Gmail](https://mail.google.com/mail/?view=cm&fs=1&tf=1&to=kunalkoleh333@gmail.com) <a href="https://mail.google.com/mail/?view=cm&fs=1&tf=1&to=kunalkoleh333@gmail.com" target="blank"><img src="https://img.icons8.com/fluency/48/gmail-new.png" alt="Kunal K" height="20" width="20"/></a> ║ [▸Facebook](https://www.facebook.com/kunal.kolhe98/) <a href="https://www.facebook.com/kunal.kolhe98/" target="blank"><img src="https://img.icons8.com/color/48/facebook-new.png" alt="Kunal K" height="20" width="20"/></a> ║ [▸Instagram](https://www.instagram.com/kkunalkkolhe/) <a href="https://www.instagram.com/kkunalkkolhe/" target="blank"><img src="https://img.icons8.com/fluency/48/instagram-new.png" alt="Kunal K" height="20" width="20"/></a>

__Owner:__ @Kunal K</center> </small>

---

## 40 Various Word Embedding Techniques in NLP:

[Demo PDF link](https://github.com/kunalk3/Prep-And-Practice/blob/main/LearningBase/DeepLearning_notes/word_embeddings_explore.pdf) 

📌 __Bag of Words (BoW):__ This technique represents text as a collection of unique words and their frequencies within a document. It ignores the order of words but considers their occurrence.

📌 __Term Frequency-Inverse Document Frequency (TF-IDF):__ TF-IDF represents text by assigning a weight to each word based on its frequency in a document and its rarity across all documents in a corpus.

📌 __Word2Vec:__ Word2Vec is a shallow neural network-based technique that learns word embeddings by predicting the context of words in a large corpus. It represents words as dense vectors in a continuous space, capturing semantic relationships between words.

📌 __Global Vectors for Word Representation (GloVe)__: GloVe is a model that learns word embeddings by factorizing the co-occurrence matrix of words. It combines global statistics of word co-occurrences with local context windows to generate word vectors.

📌 __FastText:__ FastText extends Word2Vec by representing words as bags of character n-grams. It captures morphological information and is particularly effective for handling out-of-vocabulary words.

📌 __Universal Sentence Encoder (USE):__ USE is a pre-trained deep learning model that encodes sentences or short paragraphs into fixed-length dense vectors. It captures semantic and syntactic information, making it suitable for various natural language processing tasks.

📌 __BERT (Bidirectional Encoder Representations from Transformers):__ BERT is a transformer-based model that learns contextualized word embeddings. It considers the surrounding context of each word to generate rich representations that capture both local and global semantics.

📌 __ELMo (Embeddings from Language Models):__ ELMo is a deep contextualized word representation model that generates word embeddings by combining hidden states from a bidirectional LSTM language model. It captures word meaning based on its context in a sentence.

📌 __Transformer-based Models:__ Models like GPT (Generative Pre-trained Transformer) and T5 (Text-to-Text Transfer Transformer) learn contextualized embeddings by leveraging large-scale unsupervised pre-training. They generate high-quality representations for various natural language understanding and generation tasks.

📌 __Doc2Vec:__ Doc2Vec is an extension of Word2Vec that learns fixed-length representations for entire documents, paragraphs, or sentences. It generates document embeddings by considering the context of words within the document.

📌 __Paragraph Vectors:__ Paragraph Vectors, also known as Distributed Memory Model of Paragraph Vectors (PV-DM), learns fixed-length representations for variable-length pieces of text, such as paragraphs or documents. It combines the paragraph's context with word embeddings to generate paragraph vectors.

📌 __Sent2Vec:__ Sent2Vec is a technique that learns fixed-length representations for sentences. It combines the Word2Vec model with a hierarchical softmax or negative sampling to generate sentence embeddings.

📌 __USE-Lite:__ USE-Lite is a lightweight version of the Universal Sentence Encoder that provides sentence embeddings without sacrificing much performance. It is suitable for resource-constrained environments.

📌 __InferSent:__ InferSent is a sentence embedding model that utilizes a bi-directional LSTM network trained on a large supervised dataset. It captures semantic information and performs well on various natural language processing tasks.

📌 __LASER (Language-Agnostic SEntence Representations):__ LASER is a multilingual sentence embedding method that uses a bidirectional LSTM network to generate sentence representations. It can handle multiple languages and is trained on large-scale parallel data.

📌 __XLNet:__ XLNet is a transformer-based model that overcomes the limitations of BERT by considering all possible permutations of the input words during training. It captures bidirectional context and achieves state-of-the-art results on various natural language processing tasks.

📌 __RoBERTa:__ RoBERTa is another variant of the transformer-based model, similar to BERT. It is trained on a larger dataset with longer sequences and utilizes additional pre-training techniques to improve performance.

📌 __Transformer-XL:__ Transformer-XL is a variant of the transformer model that introduces a segment-level recurrence mechanism. It enables the model to capture longer-term dependencies in the input text, making it suitable for tasks involving longer sequences.

📌 __SIF (Smooth Inverse Frequency):__ SIF is a technique that combines word embeddings with weighted averages to generate sentence embeddings. It incorporates inverse word frequency to reduce the impact of common words and focus on important content words.

📌 __USE-QA (Universal Sentence Encoder for Question-Answering):__ USE-QA is an extension of the Universal Sentence Encoder that is specifically trained for question-answering tasks. It generates embeddings that capture the meaning and context of both questions and answers.

📌 __ELMo+BERT:__ This technique combines the contextual word embeddings from ELMo with the contextualized representations from BERT. By leveraging both models, it captures a broader range of semantic and contextual information.

📌 __Sentence-BERT:__ Sentence-BERT is a modification of the BERT model that is trained specifically to generate sentence embeddings. It uses siamese and triplet network architectures to optimize the similarity between sentence embeddings.

📌 __Transformer-based Models with Pre-training:__ Apart from BERT and GPT, there are other transformer-based models that have been pre-trained on large-scale datasets. These include models like ELECTRA, ALBERT, and DeBERTa, which offer variations in architecture and pre-training objectives.

📌 __Knowledge Graph Embeddings:__ Knowledge graph embeddings represent entities and relations in a knowledge graph as continuous vectors. Techniques like TransE, TransR, and ComplEx map entities and relations to low-dimensional vector spaces to capture semantic relationships in structured data.

📌 __Contextualized Word Embeddings:__ Models like Flair and ULMFiT generate contextualized word embeddings by considering the entire sentence or document context. They capture the meaning of words based on their position within the context.

📌 __Character-based Embeddings:__ Instead of representing words as units, character-based embeddings generate embeddings for individual characters or character n-grams. These embeddings capture sub-word information and are useful for tasks like named entity recognition and morphological analysis.

📌 __Meta-Embeddings:__ Meta-embedding techniques combine multiple word embedding models to generate enriched representations. Approaches like Sent2Vec + GloVe or Word2Vec + FastText aim to leverage the strengths of different models and capture a broader range of semantic information.

📌 __Contextualized String Embeddings (CoVe):__ CoVe is a technique that leverages recurrent neural networks (RNNs) to generate word embeddings. It considers both the current word and its surrounding context to capture contextual information.

📌 __Structured Skip-Thought Vectors:__ Skip-Thought Vectors extend the idea of word2vec to generate sentence embeddings. It trains a model to predict the previous and next sentences given the current sentence, capturing the context and semantics of sentences.

📌 __Attentive Pooling:__ Attentive Pooling is a technique that uses attention mechanisms to generate sentence or document embeddings. It assigns different weights to different words based on their importance in the context, resulting in a weighted average representation.

📌 __Deep Averaging Networks (DAN):__ DAN is a neural network-based technique that generates sentence embeddings by averaging word embeddings. It applies multiple layers of non-linear transformations to capture complex relationships between words.

📌 __Hierarchical Attention Networks (HAN):__ HAN is a model that uses hierarchical attention mechanisms to capture information at different levels of granularity, such as words and sentences. It generates embeddings by attending to important words and sentences in the text.

📌 __Graph Convolutional Networks (GCN):__ GCN is a technique that represents text as a graph and applies graph convolutional operations to capture relationships between words or entities. It generates embeddings that incorporate both semantic and structural information.

📌 __Universal Transformer:__ Universal Transformer is a variant of the transformer model that applies dynamic computation steps for each token, allowing it to adaptively adjust the number of transformations based on the input. It captures long-range dependencies effectively.

📌 __Hyperbolic Embeddings:__ Hyperbolic embeddings represent words or entities in hyperbolic space rather than Euclidean space. These embeddings are effective for capturing hierarchical structures and relationships in text data.

📌 __Randomized Contextual Embeddings:__ This technique injects random noise into the input sequence during training, forcing the model to learn robust representations that are resilient to perturbations. It can improve the generalization and performance of models.

📌 __Adversarial Training for Embeddings:__ Adversarial training involves training a discriminator to differentiate between real and generated word embeddings. By optimizing the embeddings to fool the discriminator, the model can learn more informative and discriminative embeddings.

📌 __Deep Cross-Modal Hashing (DCMH):__ DCMH generates compact binary embeddings that capture the cross-modal information between text and other modalities, such as images or videos. It is useful for tasks involving multimodal data.

---

<div align="left">
<img src="https://user-images.githubusercontent.com/41562231/141720940-53eb9b25-777d-4057-9c2d-8e22d2677c7c.png" height="120" width="900">
</div>
