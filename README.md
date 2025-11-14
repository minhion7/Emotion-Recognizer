# Audio Emotion Recognizer (No-Code ML Project)

This project uses **Google Teachable Machine** to classify emotions from short speech audio clips. The model predicts three emotion categories:

- **Happy**
- **Angry**
- **Neutral**

It is an introductory machine learning project demonstrating data collection, labeling, training, evaluation, and model export without requiring prior coding experience.

---

## Project Structure

```text
model/               → exported Teachable Machine / TensorFlow Lite model
screenshots/         → training results and test predictions
project-report/      → (optional) full PDF project summary
README.md            → project documentation

## Python Audio Analysis Notebook

This project also includes a small Python notebook (`analysis/audio_features_analysis.ipynb`) that demonstrates how emotion-recognition systems process speech signals.

The notebook performs:

- **Audio loading and playback**
- **Waveform visualization**
- **Mel spectrogram generation** (the same type of input used by models like Teachable Machine)
- **Basic audio feature extraction**, including:
  - mean pitch (F0)
  - RMS energy
  - spectral centroid

These features are commonly used in machine learning models for **emotion classification**, **voice analysis**, and **affective computing**.  
This notebook shows the signal-processing steps that occur under the hood of no-code ML tools.
