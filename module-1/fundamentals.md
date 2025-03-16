# Fundamental Concepts of Generative AI

- [Fundamental Concepts of Generative AI](#fundamental-concepts-of-generative-ai)
  - [Module outcomes](#module-outcomes)
  - [Introduction](#introduction)
  - [What is Generative AI?](#what-is-generative-ai)
  - [Types of Generative AI](#types-of-generative-ai)
  - [Large Language Models (LLM)](#large-language-models-llm)
    - [Benefits of using different models](#benefits-of-using-different-models)
    - [Transformer Model](#transformer-model)
    - [Historical Comparisons](#historical-comparisons)
    - [LLM Development vs Traditional Development](#llm-development-vs-traditional-development)
  - [What is Question Answering in Natural Language Processing?](#what-is-question-answering-in-natural-language-processing)
  - [Prompts and Prompt Engineering](#prompts-and-prompt-engineering)
  - [3 kinds of Language Modules](#3-kinds-of-language-modules)
  - [Chain of Thought Reasoning](#chain-of-thought-reasoning)
  - [LLM Tuning](#llm-tuning)
    - [LLM Fine Tuning](#llm-fine-tuning)
    - [Parameter Efficient Tuning Methods (PETM)](#parameter-efficient-tuning-methods-petm)
  - [AI Principles behind LLMs](#ai-principles-behind-llms)

This course will cover the fundamentals of Generative AI and its application to various routine business functions.

## Module outcomes

Upon completion of Fundamental concepts of Generative AI module, you will be able to:

- Describe the fundamental concepts of Generative AI.

## Introduction

**General Intelligence can be seen as:**

- Knowledge and data is very important, they lead to analytical intelligence.
  - leads us into analytical intelligence.
- Creativity is the component that allows us to acquire and apply knowledge and skills.
  - leads us into generative intelligence.
- General skills lead us into cognitive intelligence.

We use all these things to complete processes, like making a bed or making a cup of tea.

**Artificial intelligence is then:**

- DIs designing and developing a system to acquire and apply knowledge and skills to complete a specific process.
- This leads us into 3 distinct AI systems:
  - Analytical AI
    - mining, ranking, rating, understanding the data.
    - understanding the data
  - Cognitive AI
    - Decision making
  - Generative AI
    - Is the capability to acquire and apply knowledge and skills to complete a specific process.

<!--- cSpell:disable --->
Artificial Intelligence is mainly _generative AI_.
Tools that use AI; Chatgpt (text), DALL-E (images), WALL-E (speech), Github Co-pilot (code).
Process, all these AI systems help in _generating_ processes, _augmenting_ processes and _improving_ the process.
<!--- cSpell:enable --->

## What is Generative AI?

Type of artificial intelligence of creating a wide range of data, such as images, videos, audio, text and 3D models. Generative AI learns patterns from existing data and then uses this knowledge to generative new and unique outputs. The output is highly realistic and can mimic humans, thereby making it a valuable tool.  

Generative AI can learn from various sources and generate new content that reflects the characteristics of the training data but does not repeat it.

- Generative AI uses several techniques that continue to evolve.  
- At a fundamental level, it uses AI models to train on a broad set of unlabelled data that can be used for different tasks, with additional fine-tuning.
- It requires complex maths and enormous computing power to train these models, the essence of their prediction algorithms. GenAI is most commonly used to create content in response to natural language requests.

## Types of Generative AI

- **Generative Adversarial Networks (GANS)**
  - GANs use deep learning in unsupervised data discovery, e.g., applications generating photorealistic images and complex but real image editing.
  - generate realistic and high-quality data, such as images, audio, and text.
- **Transformer-Based Models**
  - These are used to generate text, speech, images and other content by discerning context, meaning and patterns, e.g., ChatGPT and DALL-E.
  - are used for natural language processing (NLP) tasks, such as text generation and speech.
- **Variational Auto-encoders (VAES)**
  - VAEs comprise of two difference neural networks of encoders and decoders, e.g., security analytics, anomaly detections and signal processing.
  - are used in security analytics, anomaly detection, and signal processing.

**ChatGPT** (Chat Generative Pre-trained Transformer) foundation is **LLM** (Large Language Model). **LLM** is a computer algorithm that processes natural language inputs and predicts the next word based on what it has already seen.

## Large Language Models (LLM)

**Large Language Models** (LLMs) are AI systems that undergo extensive training on vast amounts of text data to _predict the most likely following words based on preceding words_. It's important to note that LLMs operate by _predicting language sequences_ rather than comprehending language.

LLMs are categorised into 5 principal types:

- dialogue generation
- Transition
- Knowledge Answering
- Classification
- Text Generation

What separates LLMs from previous Machine Learning architectures using supervised or unsupervised learning are **Foundation models**. Foundation models uses self-supervised learning to create labels from input data. Therefore, no-one has trained the model with labelled training data sets.  

Different data types (text, images, speech, structured data and 3D signals) train the Foundation model, enabling various Generative AI tasks, such as question answering, sentiment analysis, information extraction, image captioning, object recognition, and following instructions.

> LLMs are essentially a Transformer-based neural network.  

Some examples of LLMs include:

- GPT-3 and GPT-4
- BARD
- XLNet
- T5
- RoBERTa

Refer to this [article on large language models](https://www.techtarget.com/whatis/feature/12-of-the-best-large-language-models).  
Google video on an [Introduction to Large Language Models](https://www.youtube.com/watch?v=zizonToFXDs).  

- Large
  - Large training dataset
  - Large number of parameters
  - **parameters** are the memories/knowledge that the machine learned during the model training
- General Purpose
  - models are sufficient to solve common problems
  - commonality of the human language
  - resource restrictions (only certain companies can train such large language models with huge datasets and a tremendous number of parameters)
- Pre-trained and fine-tuned
  - **pre-train** a model with a general purpose and a large dataset and then; **fine-tune** for specific aims with a much smaller dataset

### Benefits of using different models

- A single model can be used for different tasks (PB data and Billions of parameters)
- The fine-tune process requires minimal field training data when they are tailored to solve a specific problem
  - `few shot`: training a model with minimal data
  - `zero shot`: implies that a model can recognise things that haven't been taught in the training before
- The performance of LLM is continuously growing when you add more data and parameters

### Transformer Model

The transformer model contains two components

- Encoding component, which encodes the input sequence adn passed it to the decoder
- Decoding component, which learns to decode the representations for the relevant task

### Historical Comparisons

- **Traditional**: Hard code to characteristics/variables to distinguish a cat
- **Neural**: give picture of cats and dogs and ask if it is a cat or a dog.
- **Generative**: Users generate their own content, text, images, audio, video etc

### LLM Development vs Traditional Development

LLM Development (using pre-trained APIs)

- No ML experience
- No training examples
- No need to train a model
- Thinks about prompt design

Traditional ML Development

- Yes ML Experience Needed
- Yes training examples
- Yes need to train a model
- Yes compute and hardware
- Think about minimizing a loss function

## What is Question Answering in Natural Language Processing?

**Question Answering** (QA) is a subfield of Natural Language Processing that deals with the task of automatically answering questions posed in natural language.  
Question Answering models are able to retrieve the answer to a question from a given text. Useful for searching for an answer in a document. Depending on the model used, the answer can be directly extracted from text or generated from scratch.

You need domain knowledge to develop specific areas, like logistics, IT systems etc

In **Generative QA**, this **generates free text** directly based on the context. It leverages **Text Generation Models** and there in no need for **domain knowledge**.

## Prompts and Prompt Engineering

There are two key components:

- Prompt Design
  - Prompts involve instructions and context passed to a language model to achieve a desired task.
- Prompt Engineering
  - Prompt engineering is the practice of _developing and optimising prompts to efficiently use language models_ for a variety of applications.

## 3 kinds of Language Modules

Each of the models need prompting in a different way. The _first two are easily confused_ and give very different outputs.

- **Generic (or Raw) Language Models**: These predict the next word (technically a token) based on the language in the training data.
- **Instruction Tuned**: Trained to predict a response to the instructions given in the input.
- **Dialogue Tuned**: Trained to have a dialogue by predicting the next response.

> **Dialogue-tuned models** are a special case of **instruction-tuned** where requests are typically framed as questions to a chatbot. Dialogue-tuning is expected to contextually be of a longer back-and-forth conversation and typically works better with natural question-like phrasings.  

## Chain of Thought Reasoning

Chain-of-thought reasoning is the observation that models are better at getting the right answer when they first output text that explains the reason for the answer.

## LLM Tuning

Tuning a model enables you to customise the model response based on examples of the task that you want the model to perform. It's essentially the process of adapting a model to a new domain or set of custom use cases by training the model on new data.

### LLM Fine Tuning

This is where you bring your own dataset and retrain the model by tuning every weight in the LLM. Fine tuning is expensive and not realistic in many cases.

### Parameter Efficient Tuning Methods (PETM)

Parameter-efficient tuning methods, or PETM, More efficient methods of tuning are methods for tuning a large language model on your own custom data without duplicating the model. The base model itself is not altered Instead, a small number of add-on layers are tuned which can be swapped in and out at inference time.  

**Revision**
What is the primary purpose of Large Language Models in the field of Generative AI?  
To simulate human-like conversations and generate text.

## AI Principles behind LLMs

Large language models are based on machine learning and deep learning techniques. However, you don't need to be a computer science technologist to understand the principles behind these models.
