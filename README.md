# LSTM-Based ISI Removal (Neural Equalizer)

## 🚀 Overview

This project implements an LSTM-based equalizer to remove Inter-Symbol Interference (ISI) in digital communication systems.

## 🧠 Idea

Instead of eliminating ISI using classical techniques (Nyquist, Duobinary), this project uses deep learning to **learn ISI patterns directly**.

## ⚙️ System Pipeline

Bits → PAM → ISI Channel → LSTM → Recovered Bits

## 📊 Results

* Without equalizer: BER ≈ 0.43
* With LSTM: BER ≈ 0.21

## 🛠 Tech Stack

* Python
* PyTorch
* NumPy
* Matplotlib

## 📌 How to Run

1. Install requirements:

```
pip install -r requirements.txt
```

2. Run Jupyter Notebook:

```
jupyter notebook
```

## 🔥 Future Work

* Bidirectional LSTM
* Transformer-based equalizer
* Real-time systems
