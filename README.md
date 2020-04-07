# Advanced NLP with spaCy

course website: https://course.spacy.io/

## Overview

In this course, you'll learn how to use spaCy to build advanced natural language understanding systems, using both rule-based and machine learning approaches. I originally developed the content for DataCamp, but I wanted to make a free version so you don't have to sign up for their service. As a weekend project, I ended up putting together my own little app to present the exercises and content in a fun and interactive way.

## Schedule

### [Chapter 1: Finding words, phrases, names and concepts](ch1.ipynb)
> This chapter will introduce you to the basics of text processing with spaCy. You'll learn about the data structures, how to work with statistical models, and how to use them to predict linguistic features in your text.
- Introduction to spaCy
- Getting Started
- Documents, spans and tokens
- Lexical attributes
- Statistical models
- Model packages
- Loading models
- Predicting linguistic annotations
- Predicting named entities in context
- Rule-based matching
- Using the Matcher
- Writing match patterns

### [Chapter 2: Large-scale data analysis with spaCy](ch2.ipynb)
> In this chapter, you'll use your new skills to extract specific information from large volumes of text. You''ll learn how to make the most of spaCy's data structures, and how to effectively combine statistical and rule-based approaches for text analysis.
- Data Structures(1)
- Strings to hashes
- Vocab, hashes and lexemes
- Data Structures(2)
- Creating a Doc
- Docs, spans and entities from scratch
- Data structures best practices
- Word vectors and semantic similarities
- Inspecting word vectors
- Comparing similarities
- Combining models and rules
- Debugging patterns(1)
- Debugging patterns(2)
- Efficient phrase matching
- Extracting countries and relationships

### [Chapter 3: Processing Pipelines](ch3.ipynb)
> This chapter will show you to everything you need to know about spaCy's processing pipeline. You'll learn what goes on under the hood when you process a text, how to write your own components and add them to the pipeline, and how to use custom attributes to add your own meta data to the documents, spans and tokens.
- Processing pipelines
- What happens when you call nlp?
- Inspecting the pipeline
- Custom pipeline components
- Use cases for custom components
- Simple components
- Extension attributes
- Setting extension attributes(1)
- Setting extension attributes(2)
- Entities and extensions
- Components with extensions
- Scaling and performance
- Processing streams
- Processing data with context
- Selective processing

### [Chapter 4: Training a neural network model](ch4.ipynb)
> In this chapter, you'll learn how to update spaCy's statistical models to customize them for your use case – for example, to predict a new entity type in online comments. You'll write your own training loop from scratch, and understand the basics of how training works, along with tips and tricks that can make your custom NLP projects more successful.
- Training and updating models
- Purpose of training
- Creating training data(1)
- Creating training data(2)
- The training loop
- Setting up the pipeline
- Building a training loop
- Exploring the model
- Training best practices
- Good data vs. bad data
- Training multiple labels
- Wrapping up