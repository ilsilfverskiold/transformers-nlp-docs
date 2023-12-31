# Decoder Models and Applications

Decoder models in natural language processing (NLP) are primarily designed for generating text. They excel in tasks that involve creating coherent and contextually relevant text based on a given input. These models are particularly effective in language generation, translation, and creative writing tasks.

## Pre-training Objective
- **Language Modeling**: Text Generation

## Base Models

### CTRL (Conditional Transformer Language Model)
- **Overview**: A conditional language model trained to control the style, content, and task-specific behavior of generated text.
- **Released**: September 2019
- **Developed by**: Salesforce Research.
- **Model in Hugging Face**:
  - [CTRL](https://huggingface.co/ctrl)

### GPT (Generative Pre-trained Transformer)
- **Overview**: The first iteration of the GPT series, pioneering the transformer-based language model for text generation.
- **Released**: June 2018
- **Developed by**: OpenAI.
- **Model in Hugging Face**:
  - [GPT (120M](https://huggingface.co/openai-gpt)

### GPT-2 (Generative Pre-trained Transformer 2)
- **Overview**: An improvement over GPT, known for its large scale and impressive text generation capabilities.
- **Released**: February 2019
- **Developed by**: OpenAI.
- **Models in Hugging Face**:
  - [GPT-2-small (137M)](https://huggingface.co/gpt2)
  - [GPT-2-medium (380M)](https://huggingface.co/gpt2-medium)
  - [GPT-2-large (812M)](https://huggingface.co/gpt2-large)
  - [GPT-2-xl (1.61B)](https://huggingface.co/gpt2-xl)

### Transformer XL
- **Overview**: Extends the Transformer model to better handle long-distance dependencies in text. It introduces a segment-level recurrence mechanism and a novel positional encoding scheme.
- **Released**: January 2019
- **Developed by**: Google Brain and Carnegie Mellon University.

## Tasks to Train For

### Text Generation
- **Examples**: Generating creative content, automated story writing, chatbot responses.
  - [Prompt Generator: text2image-prompt-generator](https://huggingface.co/succinctly/text2image-prompt-generator?text=landscape+of)
  - [MagicPrompt-Stable-Diffusion](https://huggingface.co/Gustavosta/MagicPrompt-Stable-Diffusion?text=landscape+of)

### Conversational AI
- **Example**: Building chatbots and conversational agents.
  - [chatbot](https://huggingface.co/satvikag/chatbot?text=Hey+my+name+is+Julien%21+How+are+you%3F)

### Language Specific Conversational AI
- **Example**: Building chatbots and conversational agents in specific languages.
  - [gpt-sw3-126m-instruct (186M)](https://huggingface.co/AI-Sweden-Models/gpt-sw3-126m-instruct?text=hej+hej)

### Language Translation
- **Example**: Though primarily for text generation, can be adapted for translating text between languages.

### Creative Writing
- **Example**: Assisting in drafting stories, poems, and other creative texts.

(!) Go [here](https://github.com/ilsilfverskiold/transformers-nlp-docs/blob/main/docs/business-cases/decoder.md) to get examples for different **business cases** for decoder models. 

The list is not exhaustive. Please visit Hugging Face Model Hub fof [GPT-2 based models](https://huggingface.co/models?other=gpt2&sort=downloads) for more.
  
