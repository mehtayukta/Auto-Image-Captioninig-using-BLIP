# AutoCaptioning and QnA for Images using BLIP

This project demonstrates how to use the `Salesforce/blip-image-captioning-large` model for generating captions for images and the `Salesforce/blip-vqa-base` model for Visual Question Answering (VQA) using the Hugging Face Transformers library.

## Overview

The project is divided into two main parts:

1. **Auto Captioning**: Automatically generating descriptive captions for an image using a pre-trained model.
2. **Visual Question Answering (VQA)**: Answering questions based on the content of an image using another pre-trained model specifically fine-tuned for VQA tasks.

By leveraging these models, we can perform advanced image understanding tasks with minimal setup.

## Requirements

- Python 3.6+
- `transformers` library
- `Pillow` (PIL) library
- `matplotlib` library (optional, for displaying images)

You can install the required libraries using pip:

```sh
pip install transformers pillow matplotlib
