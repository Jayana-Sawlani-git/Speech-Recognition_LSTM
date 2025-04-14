# 🎙️ Listen, Attend and Spell (LAS) - Speech Recognition Using Deep Learning
This project implements the Listen, Attend and Spell (LAS) architecture — a powerful end-to-end speech recognition model that transforms raw audio into human-readable text using neural networks. It integrates three core components: a Bi-directional LSTM encoder, an attention-based decoder, and an alignment mechanism that enables the model to "listen" to spoken words, "attend" to relevant parts of the input, and "spell" out the corresponding text.

💡 Designed to learn directly from data, LAS does not rely on traditional phoneme modeling or pronunciation dictionaries. Instead, it learns character-level transcription through sequence-to-sequence modeling, powered by attention.

## 🚀 Features
Encoder-Decoder architecture with attention

Fully implemented in PyTorch

Trained on real-world speech data

Character-level transcription output

End-to-end deep learning pipeline

## 📁 Dataset
This project uses a subset of the LibriSpeech dataset: specifically, the train-clean-5 portion, which contains approximately 5 hours of clean speech audio from audiobooks read by multiple speakers.

Format: FLAC audio + plain text transcription

Sample Rate: 16 kHz

Transcription Type: Character-level

**📦 Dataset link: https://www.openslr.org/12**

Make sure to download and extract the dataset into the correct directory before training.

## 🛠️ Technologies Used
Python 3

PyTorch

torchaudio

LibriSpeech dataset

Jupyter Notebook or Google Colab

## 🧠 How It Works
The encoder listens: it extracts temporal features from the input audio using Bi-directional LSTMs.

The attention module attends: it learns which part of the input to focus on during decoding.

The decoder spells: it generates the output text sequence character-by-character.
