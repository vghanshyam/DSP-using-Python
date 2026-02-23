# Digital Signal Processing (DSP)

Digital Signal Processing (DSP) is the technique of analyzing and modifying signals after converting them into digital form.

## What is a Signal?

A **signal** is any measurable quantity that varies with time, space, or another independent variable and carries information.

## Types of Signals

A signal can be:

- 🎵 **Audio Signal**  
  - Speech  
  - Music  

- 🖼️ **Image or Video Signal**  
  - Digital images  
  - Video frames  

- 📡 **Radar Signal**  
  - Reflected electromagnetic waves  
  - Target detection signals  

- 📶 **Communication Signal**  
  - I/Q samples in SDR  
  - Modulated RF signals  

- 🌡️ **Sensor Data**  
  - Temperature readings  
  - Pressure measurements  
  - Accelerometer data  

# 🎯 Why Do We Use DSP?

We use **Digital Signal Processing (DSP)** for the following reasons:

---

## 1️⃣ Noise Removal

Remove unwanted noise from signals.

**Example:**  
- Cleaning a microphone signal  
- Removing thermal noise in RF systems  

---

## 2️⃣ Filtering

Extract required frequency components from a signal.

**Examples:**  
- Low-pass filter  
- High-pass filter  
- Band-pass filter  

Filtering helps in isolating useful information and rejecting unwanted frequencies.

---

## 3️⃣ Compression

Reduce data size while preserving important information.

**Examples:**  
- MP3 (Audio Compression)  
- JPEG (Image Compression)  
- Video compression standards  

---

## 4️⃣ Feature Extraction

Extract meaningful information from signals.

**Examples:**  
- Peak detection  
- Edge detection  
- Symbol detection  
- Object detection  

---

## 5️⃣ Communication Systems

DSP is fundamental in digital communication systems.

**Key Operations:**

- Modulation (BPSK, QPSK, 16QAM)  
- Equalization  
- Timing Recovery  
- Carrier Recovery (Costas Loop)  
- Matched Filtering  

---

## 6️⃣ Image Processing

DSP techniques are widely used in image and video systems.

**Applications:**

- Edge detection  
- Image filtering  
- Image enhancement  
- Object detection  

---
# ⚙️ How Do We Use DSP?

## Step 1: Convert Analog → Digital

The first step in Digital Signal Processing is converting an analog signal into a digital signal.

### 🔄 Using ADC (Analog to Digital Converter)

An **ADC (Analog to Digital Converter)** converts a continuous-time analog signal into a discrete-time digital signal.

After conversion:

- The signal becomes a **sequence of numbers**
- Each sample represents the signal amplitude at a specific time instant

---

### 📌 Representation

Analog Signal → ADC → Digital Samples  

\[
x(t) \;\longrightarrow\; ADC \;\longrightarrow\; x[n]
\]

Where:

- \( x(t) \) = Continuous-time analog signal  
- \( x[n] \) = Discrete-time digital signal (sampled version)  
- \( n \) = Sample index  

---

