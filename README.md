**Project Title**

Music Genre Classification Using Spectrograms and Deep Learning

**Project Statement**

The goal of this project is to classify music tracks into their respective genres by leveraging deep learning models. This is achieved by converting audio signals into spectrogram data and training convolutional neural networks to recognize genre-specific patterns within them.

**Problem Statement**

Classifying music genres based on raw audio can be difficult due to variations in rhythm, tempo, and instrumentation. Traditional machine learning methods often require manual feature engineering. This project addresses the problem by transforming audio into spectrograms and using deep learning to automatically extract and learn relevant features for genre classification.

**Approach**

The approach involves preprocessing audio tracks to convert them into spectrograms, which represent the frequency components of audio over time. These spectrograms are used as input to deep learning models. Multiple convolutional neural network architectures are trained to learn distinguishing features for each music genre.

**Models Used**

Several deep learning models were implemented and compared for performance:
****CRNN**

**CRNN(Attention)**

**CNN**

**VGG16**

**VGG19**

**ResNet****

Each model was trained on the spectrogram data and evaluated based on classification accuracy and other relevant metrics.

**Dataset Description**

The dataset consists of audio tracks from various music genres. All tracks were preprocessed to ensure uniformity in duration and format. Each audio sample was then transformed into its spectrogram representation and paired with a corresponding genre label for training and evaluation purposes.

**Pipeline Overview**

Audio Preprocessing: The audio files are converted to a consistent format, with steps such as mono conversion, normalization, and trimming.

**Spectrogram Transformation:**
The processed audio is converted into spectrograms to capture frequency-based features over time.

**Model Training:** 
Deep learning models are trained using the spectrogram data as input and genre labels as targets.

**Evaluation:** 
The performance of each model is assessed using classification metrics such as accuracy, precision, recall, and F1-score.

**Key Learnings**

This project demonstrates the effectiveness of treating audio data as a time-frequency signal for classification tasks. It shows that convolutional neural networks, typically used in image tasks, can perform well when adapted to audio domain via spectrograms. The importance of proper preprocessing and model selection is also highlighted.


