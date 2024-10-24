# Text-to-Speech Model Fine-Tuning Assignment

## Objective

The purpose of this assignment is to fine-tune two text-to-speech (TTS) models:
1. One model optimized to handle technical jargon commonly used in English technical interviews (e.g., "API," "CUDA," "TTS").
2. Another model fine-tuned for a regional language of your choice.

Additionally, the assignment explores ways to optimize the model for fast inference and investigates techniques such as quantization to reduce model size without compromising performance.

## Directory Structure

```plaintext
E:/speech5
│
├── datawav         # Dataset 
├── config_english.json          # Configuration for English model
├── config_regional.json         # Configuration for regional language model
├── train_english.py             # Script for training the English TTS model
├── evaluate_english.py          # Script for evaluating the English TTS model
├── train_regional.py            # Script for training the regional language TTS model
├── evaluate_regional.py         # Script for evaluating the regional language TTS model
├── quantize_model.py            # Script for quantizing the model
└── requirements.txt             # Python dependencies


Configuration Files
English Model Configuration (config_english.json)
Regional Language Model Configuration (config_regional.json)

Installation
Clone this repository or download the files into your local directory.

Ensure you have Python installed. 
It is recommended to use a virtual environment.

Install the required dependencies by running:

pip install -r requirements.txt


Running the Code

Fine-tune the English Model
python train_english.py

Evaluate the English Model
python evaluate_english.py


Fine-tuning TTS for a Regional Language

Fine-tune the Regional Language Model
python train_regional.py

Evaluate the Regional Language Model
python evaluate_regional.py



Quantize the English Model
python quantize_model.py
