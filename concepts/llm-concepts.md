# LLM Concepts

## What is a Large Language Model?

A Large Language Model (LLM) is an AI model trained on large 
amounts of text to understand and generate human language.

LLMs are used for:
- Chatbots
- Writing
- Summarization
- Coding
- Translation
- Question answering

---

## What is a Prompt?

A prompt is the input or instruction given to an AI model.

For example:

> Explain recursion using a simple example.

The prompt tells the model what we want it to do.

---

## What is Prompt Engineering?

Prompt engineering is the process of designing and refining
prompts to get better and more consistent results from an AI
model.

A good prompt usually provides:
- Clear instructions
- Context
- Examples when necessary
- Expected output format
- Constraints

---

## What is a Token?

A token is a unit of text processed by a language model.

A token can be:
- A complete word
- Part of a word
- Punctuation
- A special character

For example, a word may be represented as one or multiple tokens
depending on the tokenizer.

Token counts affect the amount of information a model can process
and, in API usage, can affect cost.

---

## What is a Context Window?

The context window is the amount of information an AI model can
process during an interaction.

It can include:
- User prompts
- Previous conversation
- Documents
- Other information provided to the model

A larger context window allows the model to work with larger
documents and longer conversations.

---

## Training vs Inference

### Training

Training is the process of teaching a model patterns from data by
adjusting its internal parameters.

### Inference

Inference is the process of using a trained model to generate an
output.

### Simple comparison

Training → Model learns

Inference → Model is used

---

## What are Parameters?

Parameters are numerical values learned during model training.

They influence how the model processes inputs and produces
outputs.

A model with billions of parameters has a very large number of
learned numerical values.

---

## What is Fine-Tuning?

Fine-tuning is the process of further training a pretrained model
on specialized data.

It can help adapt a general model to a particular task or domain.

For example:

General model
     ↓
Specialized training data
     ↓
Fine-tuned model
     ↓
Better performance on a specific task

---

## What is AI Hallucination?

An AI hallucination occurs when an AI model produces information
that sounds plausible but is incorrect, unsupported, or fabricated.

Examples include:
- Inventing a citation
- Giving an incorrect fact
- Creating a non-existent reference

AI-generated information should therefore be verified when
accuracy is important.

---

## What is RAG?

RAG stands for Retrieval-Augmented Generation.

It allows an AI application to retrieve relevant information from
an external knowledge source before generating an answer.

### Basic flow

User Question
      ↓
Retrieve Relevant Information
      ↓
Provide Information to LLM
      ↓
Generate Answer

RAG is useful when an AI application needs to work with specific
documents or external knowledge.

---

## What are Embeddings?

Embeddings are numerical representations of information that
capture semantic meaning.

Similar concepts can have similar representations in the
embedding space.

Embeddings are commonly used for:
- Semantic search
- Recommendation systems
- RAG

---

## What is a Vector Database?

A vector database stores and searches numerical vector
representations called embeddings.

Instead of searching only for exact words, it can search for
information that is semantically similar to a query.

Vector databases are commonly used in RAG applications.

---

## What is Agentic AI?

Agentic AI refers to AI systems that can perform multiple steps
toward achieving a goal.

Unlike a simple question-and-answer system, an AI agent may:
- Use tools
- Read files
- Search for information
- Call APIs
- Execute actions
- Make decisions between steps

### Simplified flow

Goal
 ↓
Plan
 ↓
Use Tool
 ↓
Observe Result
 ↓
Next Action
 ↓
Final Result

---

## What I Learned

The main concepts I learned are:

- Prompts tell AI models what to do.
- Tokens are the units processed by language models.
- Context windows determine how much information a model can
  consider at once.
- Training teaches a model patterns.
- Inference uses the trained model.
- Fine-tuning adapts a pretrained model to specialized tasks.
- Hallucinations are incorrect outputs that may sound convincing.
- RAG gives an AI system access to external information.
- Embeddings represent meaning numerically.
- Vector databases allow semantic search.
- Agentic AI allows models to perform multi-step tasks.