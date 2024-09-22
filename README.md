# Financial News Summarization with Fine-Tuned LLaMA Model

This repository contains a notebook for fine-tuning the LLaMA model to summarize financial news articles and analyze their impact on stock markets and specific sectors.

## Description

In today's fast-paced world, financial news is readily available from numerous sources, but many people struggle to find the time to sift through extensive articles and reports. As a result, understanding the impact of recent developments—such as economic indicators, earnings reports, and geopolitical events—can be challenging. This fine-tuned LLaMA 2 model addresses this need by summarizing complex financial news into concise and accessible summaries. By distilling key insights, the model helps users quickly grasp how various events influence stock markets and specific sectors, making it an invaluable tool for anyone looking to stay informed without dedicating hours to reading.


## Overview

- **Objective**: To train a model that provides concise summaries of financial news articles, explaining how recent events impact stock markets and specific sectors.
  
- **Model**: LLaMA, fine-tuned with financial news data.
  
- **API Used**: The Gemma2 9b model was utilized for data generation, it is accessed through the Groq API.

## Issues Encountered

- **Model Usage**: Due to budget constraints for purchasing OpenAI API credits, I was unable to use the GPT-4 model for dataset generation. Instead, I used the Gemma2 9b model from the Groq API.

- **Google Drive Authentication**: While trying to save the fine-tuned model to Google Drive, I encountered difficulties in receiving the authentication codes required to grant Colab access. As a workaround, I saved the fine-tuned model in the Colab directory instead.

- **Loading Errors**: When attempting to load the fine-tuned model from the Colab directory, I faced several errors that could not be resolved in the available time.




























The initial notebook was created by by [Matt Shumer](https://github.com/mshumer/gpt-llm-trainer).
