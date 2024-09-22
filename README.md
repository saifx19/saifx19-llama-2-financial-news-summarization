# Financial News Summarization with Fine-Tuned LLaMA Model

This repository contains a notebook for fine-tuning the LLaMA model to summarize financial news articles and analyze their impact on stock markets and specific sectors.


## Overview

- **Objective**: To train a model that provides concise summaries of financial news articles, explaining how recent events impact stock markets and specific sectors.
  
- **Model**: LLaMA, fine-tuned with financial news data.
  
- **API Used**: The Gemma2 9b model was utilized for data generation, it is accessed through the Groq API.

## Issues Encountered

- **Model Usage**: Due to budget constraints for purchasing OpenAI API credits, I was unable to use the GPT-4 model for dataset generation. Instead, I used the Gemma2 9b model from the Groq API.

- **Google Drive Authentication**: While trying to save the fine-tuned model to Google Drive, I encountered difficulties in receiving the authentication codes required to grant Colab access. As a workaround, I saved the fine-tuned model in the Colab directory instead.

- **Loading Errors**: When attempting to load the fine-tuned model from the Colab directory, I faced several errors that could not be resolved in the available time.




























The initial notebook was created by by [Matt Shumer](https://github.com/mshumer/gpt-llm-trainer).
