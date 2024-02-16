# Training

This code is tailored for training a speech recognition model. It commences by loading data from a CSV file and preprocessing the transcripts. Using a custom vocabulary, it creates a processor. It subsequently loads audio files, prepares the dataset, and defines data collation. The model is loaded, with its feature encoder being frozen. Configurable training arguments are set, and the Trainer initializes the training process. Ultimately, the model is quantized and saved.

# Cleaning

The purpose of this code is to cleanse a CSV file. It reads the CSV file, manages its columns, and filters out rows with empty transcripts. The sanitized data is then saved to a new CSV file.

# Live Audio Transcriptions

This code is developed for real-time transcription of live audio. It leverages the Wav2Vec2 model for transcription and integrates Tortoise TTS for voice replication. Following audio transcription, the recorded speech is converted into synthesized speech using a chosen voice.

# Augmentation

This code specializes in augmenting audio data by introducing noise, altering playback speed, and adjusting pitch. It effectively loads audio files, applies these augmentations, and archives the augmented files. These augmentations encompass noise injection, speed modification, and pitch modulation.
