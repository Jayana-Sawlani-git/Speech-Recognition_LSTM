**Listen, Attend and Spell (LAS) Model**
🎧 Listen, Attend and Spell (LAS) — End-to-End Speech Recognition with PyTorch
Transform raw audio into written text using deep learning! This project brings the power of sequence-to-sequence models with attention mechanisms to speech recognition, following the LAS (Listen, Attend and Spell) architecture.

🚀 Built from scratch with PyTorch, this project teaches your model to "listen" to speech, "attend" to important audio features, and "spell" the corresponding text — all in one elegant pipeline.

**🗂️ Dataset**
We use a curated subset of the popular LibriSpeech dataset — train-clean-5 — perfect for training and testing small to mid-scale speech recognition models.

Format: .flac audio files & their text transcripts

Source: LibriSpeech ASR corpus (http://www.openslr.org/12)

Preprocessing: Audio → Mel Spectrograms using torchaudio

**🔍 Features**

📦 Custom PyTorch Dataset for LibriSpeech

🎯 Sequence-to-sequence model with attention

🧠 Bidirectional LSTM Encoder + Attention-based Decoder

⚡ Works with variable-length audio & padded batches

🛠️ Easy to train & extend

