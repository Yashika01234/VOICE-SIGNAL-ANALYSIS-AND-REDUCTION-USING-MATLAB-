 <div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=gradient&customColorList=12,20,24&height=150&section=header&text=Voice%20Analysis&fontSize=42&fontColor=ffffff&animation=fadeIn" width="100%"/>

### a little signal processing magic with MATLAB

*Turning noisy voices into clearer sounds, one frequency at a time.*

<img src="https://img.shields.io/badge/MATLAB-DSP-9B5DE5?style=for-the-badge&logo=mathworks&logoColor=white"/>
<img src="https://img.shields.io/badge/Speech-Processing-EC8FB4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Audio-Enhancement-C4A1FF?style=for-the-badge"/>

</div>

---

## About the Project

What if we could understand a voice signal beyond just hearing it?

This project explores the world of **Digital Signal Processing (DSP)** using MATLAB. It analyzes recorded speech, studies its frequency characteristics and reduces unwanted background noise to produce an enhanced audio signal.

A small project exploring how mathematics, signals and technology come together.

## What does it do?

| Feature | Description |
|:---|:---|
| Audio Processing | Reads and preprocesses voice recordings |
| Noise Reduction | Suppresses background noise |
| Frequency Analysis | Studies frequency components |
| Waveform Analysis | Visualizes amplitude variations |
| Spectrogram | Observes frequency changes over time |
| RMS Analysis | Measures signal energy |
| Zero Crossing Rate | Studies signal sign changes |
| Spectral Centroid | Estimates spectral brightness |

## The DSP Journey

<div align="center">

`Noisy Voice`

↓

`Audio Preprocessing`

↓

`Butterworth Bandpass Filter`

↓

`Short-Time Fourier Transform`

↓

`Spectral Subtraction`

↓

`Inverse STFT`

↓

**Enhanced Voice**

</div>

## Technologies & Concepts

<div align="center">

**Tools**

<img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white"/>
<img src="https://img.shields.io/badge/Signal%20Processing-9B5DE5?style=flat-square"/>
<img src="https://img.shields.io/badge/Audio%20Analysis-EC8FB4?style=flat-square"/>

**DSP Concepts**

`FFT` · `STFT` · `IFFT` · `FIR/IIR concepts` · `Butterworth Filtering` · `Spectral Subtraction` · `RMS` · `ZCR`

</div>

## Project Structure

```text
Voice-Analysis-DSP/
│
├── voice_analysis.m
├── README.md
├── noisy_voice.wav
└── clean_voice.wav
```

- `voice_analysis.m` — Main MATLAB implementation.
- `noisy_voice.wav` — Input audio recording.
- `clean_voice.wav` — Generated enhanced recording.

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/YOUR_USERNAME/Voice-Analysis-DSP.git
```

**2. Open the project in MATLAB**

**3. Add your audio recording**

Place a WAV file named `noisy_voice.wav` in the project directory.

The first 0.5 seconds should contain background noise without speech for noise estimation.

**4. Run the script**

```matlab
voice_analysis
```

**5. Listen to the result**

The enhanced recording is saved as `clean_voice.wav`.

## Requirements

- MATLAB R2021b or later recommended.
- Signal Processing Toolbox.
- WAV-format audio recording.

## A Little More About the DSP

<details>
<summary><b>01. Butterworth Filtering</b></summary>

A bandpass filter retains the selected speech frequency range while suppressing unwanted low and high frequency components.

</details>

<details>
<summary><b>02. Short-Time Fourier Transform</b></summary>

STFT helps understand how the frequency components of a voice signal change over time.

</details>

<details>
<summary><b>03. Spectral Subtraction</b></summary>

An estimated noise spectrum is subtracted from the noisy speech magnitude spectrum to suppress background noise.

</details>

<details>
<summary><b>04. Voice Signal Analysis</b></summary>

RMS, peak amplitude, zero-crossing rate, dominant frequency and spectral centroid are calculated to understand the characteristics of the audio signal.

</details>

## Future Possibilities

- Real-time microphone-based noise reduction.
- Wiener filtering.
- Adaptive noise cancellation using LMS.
- Pitch and fundamental frequency detection.
- SNR-based performance evaluation.
- Interactive MATLAB GUI.

---

<div align="center">

### Made with curiosity, MATLAB & a little love for engineering.

**Yashika Nanda**

Electronics & Communication Engineering

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" width="100%"/>

</div>
