# Custom-Spacy-Sentiment-Model

![social_default-1d3b50b1eba4c2b06244425ff0c49570](https://user-images.githubusercontent.com/66754032/94864408-8bb05680-0401-11eb-9a93-298cd02a1e53.jpg)

spaCy is an open-source software library for advanced natural language processing, written in the programming languages Python and Cython. 

# An NLP pipeline in spaCy has 3 components:
- Tagger (POS Tagger): Is a piece of software that reads text in some language and assigns parts of speech to each word (and other token), such as noun, verb, adjective, etc.,
- Parser ( Dependency Parser): Dependency parsing is the task of extracting a dependency parse of a sentence that represents its grammatical structure and defines the relationships between “head” words and words, which modify those heads.
- NER (Named Entity Recognition): Named-entity recognition is a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into pre-defined categories such as person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc.

- Please go though this link to learn more about spaCy: https://spacy.io/usage/training

Our main agenda is to implement a custom sentiment model for capturing the sentiment of tweets using the specific portion of the text. Generating train dataset is the major challenge for NLP modeling problems. We have used Prodigy (https://prodi.gy/) to create our own dataset for training the text dataset.

We have used Jaccard Similarity metric to evaluate the text similarity!


Happy Coding!


