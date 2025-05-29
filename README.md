# PyTorch ASR Phoneme Extraction

This repository contains code examples for extracting phoneme representations from speech using PyTorch and pre-trained ASR models.

## Overview

The Jupyter notebook demonstrates:
- Loading and processing audio files
- Using Wav2Vec 2.0 models for speech recognition
- Extracting phoneme probabilities from ASR models
- Visualizing phoneme activations over time
- Decoding phoneme sequences to text

## Requirements

```
torch
torchaudio
transformers
matplotlib
numpy
ipython
jupyter
```

## Getting Started

### Option 1: Direct Installation

1. Clone this repository
2. Install the requirements: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook pytorch_asr_phonemes.ipynb`

### Option 2: Using a Virtual Environment

To use a virtual environment:

1. Clone this repository
2. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```
3. Activate the virtual environment:
   ```bash
   # On Linux/macOS:
   source .venv/bin/activate
   # On Windows:
   # .venv\Scripts\activate
   ```
4. Install ipykernel to make the venv available to Jupyter:
   ```bash
   pip install ipykernel
   ```
5. Register the kernel with Jupyter:
   ```bash
   python -m ipykernel install --user --name=asr-phonemes-venv
   ```
6. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
7. Run Jupyter and select the 'asr-phonemes-venv' kernel:
   ```bash
   jupyter notebook pytorch_asr_phonemes.ipynb
   ```

## Sample Data

The repository includes a small sample audio file for testing the code.

## Related Blog Post

For more information, see the full blog post: [ASR with PyTorch: Exploring Phoneme Representations](https://mcgarrah.org/pytorch-asr-example/)