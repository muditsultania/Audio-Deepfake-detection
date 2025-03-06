# Audio Processing and Visualization Project

This project focuses on processing audio files, reducing noise, and visualizing the results using Mel Spectrograms. The project leverages several powerful libraries to achieve these tasks.

## Libraries Used

- **Librosa**: A Python package for music and audio analysis. It provides the building blocks necessary to create music information retrieval systems.
- **Soundfile**: A library to read and write sound files. It supports various file formats such as WAV, FLAC, and OGG.
- **Matplotlib**: A plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications.
- **NumPy**: A fundamental package for scientific computing with Python. It contains among other things a powerful N-dimensional array object.

## Project Structure

- **Audio Loading**: The audio file is loaded using `librosa.load`.
- **Original Audio Saving**: The original audio is saved using `soundfile.write`.
- **Original Mel Spectrogram**: The Mel Spectrogram of the original audio is generated and displayed using `librosa.feature.melspectrogram` and `librosa.display.specshow`.
- **Noise Reduction**: Noise reduction is performed using a custom function `denoise_and_amplify`.
- **Final Mel Spectrogram**: The Mel Spectrogram of the noise-reduced audio is generated and displayed.

## Usage

To use the function, simply call `preprocess_and_visualize` with the path to your audio file:

```python
file_path = 'A_2582_0_A.wav'
preprocess_and_visualize(file_path)
```

## Results
![image](https://github.com/user-attachments/assets/038c01ef-ff82-43b9-b7f2-bd9f851e6b9c)


