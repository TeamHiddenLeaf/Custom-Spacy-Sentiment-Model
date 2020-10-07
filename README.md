# Unlocking the blackbox of sentiment analysis framework using spaCy

![social_default-1d3b50b1eba4c2b06244425ff0c49570](https://user-images.githubusercontent.com/66754032/94864408-8bb05680-0401-11eb-9a93-298cd02a1e53.jpg)

spaCy is an open-source software library for advanced natural language processing, written in the programming languages Python and Cython. 

# An NLP pipeline in spaCy has 3 components:
- Tagger (POS Tagger): Is a piece of software that reads text in some language and assigns parts of speech to each word (and other token), such as noun, verb, adjective, etc.,
- Parser ( Dependency Parser): Dependency parsing is the task of extracting a dependency parse of a sentence that represents its grammatical structure and defines the relationships between “head” words and words, which modify those heads.
- NER (Named Entity Recognition): Named-entity recognition is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc.

- Please go though this link to learn more about spaCy: https://spacy.io/usage/training

### Our main agenda is to implement a custom sentiment model to predict the words/word in a text that ultimately decides/influences the sentiment/emotion of a text . 


To acheive this, we are using self-annotated dataset using Prodigy. The train dataset has following columns/attributes:

1. textID: text identifier
2. text: review/tweets in the form of text
3. sentiment: The emotion associated with the text (Positive, Negative, and Neutral)
4. selected_text: Part of text that plays a major contribution in deciding the sentiment of the text

The test dataset has following columns/attributes:

1. textID: text identifier
2. text: review/tweets in the form of text
3. sentiment: The emotion associated with the text(Positive, Negative, and Neutral)
4. selected_text: Predict the word/words that influence the polarity of the text

### Train dataset snapshot

<img width="492" alt="Capture" src="https://user-images.githubusercontent.com/66754032/95028113-8a7e6400-0663-11eb-9cfe-55e4d2ee373d.PNG">

### Prediction snapshot

<img width="541" alt="Capture" src="https://user-images.githubusercontent.com/66754032/95028170-f2cd4580-0663-11eb-8311-29378dbd72b3.PNG">

We have used Jaccard Similarity metric to evaluate the text similarity!

Credits: Rohit Singh Kaggle


Happy Coding!


