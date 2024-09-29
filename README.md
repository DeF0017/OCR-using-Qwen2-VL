# OCR-using-Qwen2-VL

This project implements Optical Character Recognition (OCR) using the **Qwen2-VL-2B** model from Hugging Face. The model is capable of extracting text from both images and videos, with an option to highlight specific keywords in the extracted text. A web interface is provided using **Gradio** for easy interaction.

## Features

- **OCR on Images and Videos**: Upload images or videos to extract text.
- **Keyword Search and Highlighting**: Search for specific words in the extracted text, and see them highlighted in the output.
- **Gradio Interface**: Simple, intuitive web interface built using Gradio.
- **GPU Acceleration**: Leverages GPU for faster inference.

## Model

The [Qwen2-VL-2B Instruct](https://huggingface.co/Qwen/Qwen2-VL-2B-Instruct) model is a state-of-the-art multimodal transformer capable of understanding and generating text from images and videos.

## How It Works

1. **Input Media**: Users can upload images (JPG, PNG) or videos (MP4, AVI, etc.).
2. **Text Extraction**: The **Qwen2-VL-2B** model extracts text from the media.
3. **Keyword Highlighting**: If a keyword is provided, occurrences are highlighted using regular expressions.
4. **Output Display**: The extracted and highlighted text is displayed in the Gradio interface.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/qwen2-vl-ocr.git
cd qwen2-vl-ocr
