# 🎛️ 3-Band Equalizer Plugin (C++ & JUCE Framework)

This project is a modern C++ implementation of a 3-band equalizer with a real-time spectrum analyzer, built using the [JUCE Framework](https://juce.com/). The project was developed by following the **Learn Modern C++ by Building an Audio Plugin** course by [Matkat Music](https://www.youtube.com/matkatmusic).

  <img src="images/SimpleEQ1.gif" alt="Project Image" width="450">

## 📜 Project Overview
The equalizer plugin allows users to adjust three frequency bands: low, mid, and high, offering precise control over the sound spectrum. In addition, a real-time spectrum analyzer helps visualize audio signals as users interact with the equalizer.

### 🎚️ Features

#### 3-Band Equalizer
- **Low-Cut Band:** Adjusts the low frequencies.
- **Parametric Mid Band:** Controls the mid frequencies with gain and frequency adjustments.
- **High-Cut Band:** Adjusts the high frequencies.

#### Spectrum Analyzer
- Displays real-time visualization of audio signals.
- Helps users understand how frequency adjustments affect the audio spectrum.

#### User Interface (UI)
- **Sliders:** Allow for fine-tuning of frequencies and gain for each band.
- **Bypass Buttons:** Activate/deactivate each frequency band independently.
- **Response Curve:** Visually shows the effect of the equalizer on the audio spectrum in real-time.

## 🔧 Technologies Used
- **C++ (Modern):** Core programming language for the plugin.
- **JUCE Framework:** Provides the audio processing, GUI, and plugin development tools.

## 🚀 How to Run
1. Clone the repository.
2. Install the JUCE Framework.
3. Open the project in your preferred IDE (e.g., Visual Studio, Xcode).
4. Build the project to create the plugin (VST, AU, etc.).
5. Load the plugin in a DAW (e.g., Ableton, FL Studio) to test the equalizer.

  <img src="images/SimpleEQ2.gif" alt="Project Image" width="600">


## 🔗 Credits
This project was created following the course by [Matkat Music](https://www.youtube.com/matkatmusic). Check out his work on:
- YouTube: [Matkat Music](https://www.youtube.com/matkatmusic)
