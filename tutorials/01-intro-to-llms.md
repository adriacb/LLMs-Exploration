# Introduction to Large Language Models (LLMs)

## Overview
This readme document provides an introduction to Large Language Models (LLMs), the driving force behind recent advancements in artificial intelligence. It covers fundamental concepts, LLM architecture, and highlights popular LLMs currently available.

## Table of Contents
1. [What Are Large Language Models?](#what-are-large-language-models)
2. [Language Modeling (LM)](#language-modeling)
3. [Large Language Models (LLMs)](#large-language-models)
4. [LLMs and Foundation Models](#llms-and-foundation-models)

## 1. What Are Large Language Models?
Historically, computers were limited to understanding a defined set of instructions, typically written in programming languages like Java. However, as computing technology advanced, the need for computers to comprehend natural language commands, such as English, became apparent.

Large language models (LLMs) are deep learning algorithms capable of recognizing, summarizing, translating, predicting, and generating text and other content based on extensive dataset knowledge. They find applications beyond language understanding, including tasks in healthcare, software development, and various fields. 

LLMs extend their capabilities to areas like computer code and biology, enabling innovative solutions and creativity. They play a crucial role in diverse applications such as drug discovery, content generation, and reimagining search engines, enhancing AI's reach and impact across industries.

### 1.1. Beginning of NLP
Natural Language Processing (NLP) is an interdisciplinary subfield of linguistics, computer science, and artificial intelligence. Its goal is to enable computers to understand texts and other media in their natural languages, including their contextual nuances.

- The roots of NLP can be traced back to the 1950s when Alan Turing introduced the Turing test as a measure of artificial intelligence. In the early stages, NLP relied on rule-based approaches to emulate natural language understanding.

- In the 1980s, advancements in computational power and the adoption of machine learning techniques for language processing led to the development of statistical NLP. Initially, supervised learning was used, particularly in machine translation. However, the field shifted towards semi-supervised and unsupervised learning as the internet generated vast amounts of raw language data. 

- A key tool in NLP applications is language modeling.

### 1.2. Language Modeling (LM)
- LM uses statistical and probabilistic techniques to determine the probability of word sequences in sentences, represented as P(x^{(t+1)}|x^{(t)},...,x^{(1)}).

- **Text Corpus:** Language models generate probabilities by learning from one or more text corpora, large structured sets of texts in one or multiple languages.

- **N-gram Approach:** One of the earliest language modeling approaches uses n-grams, where the probability of the next word depends on a fixed-size window of previous words.

- **Neural Language Models:** Neural language models, based on neural networks, employ continuous representations of words to make predictions. They avoid the curse of dimensionality in language modeling.

- **Architectures:** Several neural network architectures (RNN, LSTMs, GRUs) have been proposed for language modeling, offering flexibility and improvements over traditional n-gram models.

### 1.3. LLMs and Foundation Models
- **Foundation Models**: These models, trained on diverse data, can adapt to various downstream tasks. They utilize deep neural networks and self-supervised learning on unlabeled data. Coined recently by the Stanford Institute for Human-Centered Artificial Intelligence (HAI).

- **Relation to LLMs**: While there is no clear distinction, LLMs are usually trained on language-related data, whereas foundation models encompass multimodal data, including text, images, and audio. Foundation models serve as the base for more specific tasks.

- **Fine-Tuning**: Foundation models are typically fine-tuned for different related tasks, a process known as transfer learning. It involves taking a pre-trained language model and training it further with specific data for new applications.

## 2. General Architecture of LLMs

The early large language models (LLMs) primarily employed RNN models featuring LSTMs and GRUs, as previously mentioned. However, these models encountered difficulties, particularly when it came to handling large-scale NLP tasks. Ironically, this was the precise domain where LLMs were anticipated to shine, prompting the emergence of Transformers.