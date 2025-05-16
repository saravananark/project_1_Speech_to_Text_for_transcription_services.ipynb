# project_1_Speech_to_Text_for_transcription_services.ipynb
The file you've uploaded is a Jupyter Notebook named:

**`project_1_Speech_to_Text_for_transcription_services.ipynb`**

---

### 📦 **Setup & Installation**

The notebook starts by installing required Python packages:

* `kaggle`, `transformers`, `torchaudio`, `librosa`, `noisereduce`, and `openai-whisper`
* `datasets` from Hugging Face

### 📁 **Data Upload**

It prompts the user to upload a dataset manually via Colab using `files.upload()`.

---

### 🧹 **Module 1: Data Cleaning**

* Loads an audio file using `librosa`.
* Removes silence using `librosa.effects.trim()`.
* Normalizes the audio signal.
* Visualizes the cleaned waveform using `matplotlib`.

---

### 📊 **Module 2: Data Analysis**

* Plots a **spectrogram** of the cleaned audio to visually inspect quality (e.g., noise or distortion).
* Notes an intention to analyze accents and misclassifications, but the code focuses on visualizations.

---
