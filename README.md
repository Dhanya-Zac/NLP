# NLP
Different traditional NLP approaches are 
- Linguistic Rules: These are manually created rules based on the structure and grammar of a language to process and understand text ( rule: a verb follows a noun).
- Handcrafted Features: Features manually designed by experts to capture important aspects of the text, such as word frequency or part-of-speech tags.
- Statistical Models: Models that use statistical methods to analyze and interpret text data. An example is the bag of words model, which represents a document as an unordered set of words, ignoring the order and structure of the words. It loses information about the order and context of words.
# NLP Libraries
- NLTK (Natural Language Toolkit): Foundational library for text processing tasks like tokenization, stemming, lemmatization, and stop word removal.
- spaCy: Similar to NLTK but optimized for performance and easier to use, especially for large datasets.
- Gensim: Focuses on topic modeling and document similarity, with some text pre-processing utilities.
- TextBlob: Offers core NLP functionalities and is simple to use, making it great for beginners.

For deep learning tasks in NLP:

- TensorFlow: Comprehensive framework supporting transformers.
- PyTorch: Easier to use than TensorFlow.
- MXNet and JAX: Moderate learning curve.
- Keras: Easiest to use among deep learning libraries.

#Transformer
Transformer, is a neural network architecture used in natural language processing. 
The transformer is made up of two parts, an encoder and a decoder. The encoder takes a sequence of input data, such as a sentence in a language, and converts it into a sequence of vectors. To preserve the positional information of words in the input sequence, transformers incorporate positional encoding vectors. These vectors provide information about the position of each word in the sequence and are added to the word embeddings before feeding them into the transformer layers. This ensures that the transformer can distinguish between words based on their position in the sequence. The core of the encoder neural network consists of multiple identical layers of transformer blocks. Each transformer block typically includes two main sub components, the self-attention mechanism, and the feed forward neural network. The self-attention mechanism allows each token in the sequence to attend to all other tokens, capturing dependencies and relationships between words at different positions in the sequence. 
<img width="802" height="471" alt="image" src="https://github.com/user-attachments/assets/3b76418b-4eba-4999-b1f9-d48e48a0ad35" />

