# AI principles behind LLMs

Large language models are based on machine learning and deep learning techniques. However, you don't need to be a computer science technologist to understand the principles behind these models.

## LLM Principles

LLMs focus on understanding text and the language. We got back to the fact that language is everything in relation to communication. Humans have abstract language, which is used for interactions that aren't based purely on written languages. Humans are capable of passing on knowledge from generation to generation, which makes them unique. This type of knowledge transfer can be considered **general Knowledge**. Then there is **specific knowledge**, say for example someone that wants to become a medical doctor, this requires a specific path and a certain method to acquire that knowledge. **Acquiring and applying** this knowledge is **creativity**. **Creativity** mainly focuses on problem solving, decision making, understanding complex problems and ideation. This is the main area of knowledge transfer during a PhD, or being in the workforce and becoming proficient in your industry, this helps you become a **critical thinker**. **Collective learning** is very important as it relates back to **language**. Therefore language is an important concept for intelligent entities.  

So understanding language and communication helps with the language models, LLMs specifically try to understand conversation and text.  

An example, if you have an email, then you can use an LLM to extract actions and activities from the email and assign them, as high priority, or for action in the following week etc.  

Understanding and analysing these texts provides us important opportunities. Most of the process is based on trying to understand text and natural language.

## Neural Networks

Large language models use a special neural network architecture that resembles how neurons connect in the human brain. This means the LLMs can predict and process language accurately and quickly.  

### Self-supervised learning  

Self-supervised learning is a method used to train large language models (LLMs). It involves exposing those models to vast amounts of data, often called training data. The model doesn't receive explicit labels or instructions about what it should learn during the training process. Instead, it learns to understand language patterns and structures from data. This training allows the model to learn to process the language accurately and is called self-supervised learning.

### Reinforcement Learning from Human Feedback (RLHF)  

Reinforcement Learning from Human Feedback (RLHF) is an advanced technique used in training AI models, particularly in the context of natural language understanding and generation. RLHF is a form of machine learning where an AI model learns and improves it's performance through a feedback loop, an iterative approach.

LLMs like ChatGPT employ RLHF to enhance the model's response to user input. Therefore, ChatGPT doesn't merely respond to the input text but it considers the context and user intentions from previous conversations. Therefore the responses are contextually relevant and user-specific, making it more efficient in natural language understanding and generation.

The four stages of RLHF are:

- **Initial Training**: Initially, the language model is pre-trained on a massive dataset, as with self-supervised learning. During this pre-training phase, the model learns to understand language, grammar, context, and various language patterns.
- **Fine-tuning**: After pre-training, the model is fine-tuned using reinforcement learning techniques. This involves using human-generated feedback to refine the model's responses. In reinforcement learning, the model receives feedback through rewards or penalties based on the quality of its responses. For example, if the model generates a response that aligns well with user intent and context, it receives a reward. Conversely, if the response is inaccurate or irrelevant, it gets a penalty.
- **Iterative process**: The fine-tuning process is often iterative, involving multiple rounds of training and feedback. The model continues to learn and adapt based on the feedback it receives. Over time, it becomes better at generating contextually relevant and accurate responses.
- **User intent alignment**: RLHF allows the model to align its responses with user intentions specified in the input text. This means that when a user provides context or specific information in their message, the model can use that information to generate more contextually appropriate responses.

## Emergent abilities

The idea of "emergent abilities" in large language models (LLMs) is fascinating in AI research. It refers to the unexpected and unpredictable skills or capabilities these models develop as they scale up in size and complexity.  
Reference to research paper: [Emergent Abilities of Large Language Models](https://arxiv.org/pdf/2206.07682)  

The research paper discusses how these emergent abilities challenge our understanding of language models and their scalability. It suggests there is **still much to explore** in this area and that **further scaling could lead to even more surprising and valuable capabilities** in LLMs. When LLMs are scaled up, they tend to exhibit abilities not explicitly programmed or trained for. These abilities often have unpredictable performance once the model reaches a sufficiently large scale. Therefore you can't extrapolate from the behaviour of smaller-scale models.

> The concept of "emergent abilities" in LLMs highlights large language models' intriguing and somewhat unpredictable nature as they evolve and scale. These unexpected skills open up new possibilities for what these models can achieve and contribute to ongoing research in artificial intelligence.

Next Chapter: [History of ChatGPT and OpenAI](./module-1/ChatGPT-History.md)
