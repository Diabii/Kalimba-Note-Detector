# Kalimba Note Detector

A simple Python application for detecting notes played on a kalimba ("thumb piano") using audio input from a file or live microphone. The program performs frequency analysis (FFT) to identify the dominant frequency and maps it to the closest kalimba note.

## Features

* Audio analysis from file (`.wav`, `.mp3`)
* Real-time note detection from microphone
* FFT-based dominant frequency extraction
* Mapping to kalimba notes (C major tuning)
* GUI built with CustomTkinter
* Frequency spectrum visualization (Matplotlib)

## Tech Stack

* Python
* NumPy
* Librosa
* SoundDevice
* Matplotlib
* CustomTkinter

## How It Works

1. Load or record audio
2. Compute FFT of the signal
3. Extract dominant frequency
4. Match it to the nearest predefined kalimba note

## Notes

* Designed for kalimbas tuned in C major
* Works best with clean, single-note input
