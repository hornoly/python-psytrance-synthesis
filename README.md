# Python Sound Synthesis – Psy Trance

*A Python-based electronic music synthesis project exploring digital audio generation, rhythmic sequencing, and algorithmic sound design.*

## Overview

This project explores the fundamentals of digital sound synthesis by creating a Psy Trance-inspired electronic music sequence using Python.

Rather than relying on a traditional Digital Audio Workstation (DAW), the project generates and manipulates audio signals directly through numerical computation.

Using **NumPy** and **sounddevice**, I implemented three essential elements of electronic music — Kick, Bass, and Lead — and combined them into a rhythmic musical sequence.

The project was inspired by my interest in live coding, algorithmic composition, and the relationship between programming and electronic music production.

## Technologies Used

- **Python** – Audio generation and sequencing
- **NumPy** – Waveform synthesis and numerical signal processing
- **sounddevice** – Audio playback
- **Jupyter Notebook** – Development and experimentation
- **Logic Pro** – Initial musical structure planning

## Key Features

### 1. Kick Drum Synthesis

- Generated kick sounds using sine waves.
- Applied frequency sweeps to create percussive characteristics.
- Implemented amplitude envelopes for individual beats.
- Constructed a four-on-the-floor rhythmic pattern.

### 2. Rolling Bass Synthesis

- Generated bass sounds using sawtooth waveforms.
- Implemented rhythmic gating synchronized with BPM.
- Applied a simplified sidechain-style amplitude control based on the kick signal.
- Adjusted bass dynamics to improve the balance between kick and bass.

### 3. Lead Melody Generation

- Generated melodic sequences using arrays and loops.
- Applied decay envelopes to individual notes.
- Implemented repeating melodic patterns using modular indexing.

### 4. Audio Mixing

- Combined Kick, Bass, and Lead into a single audio signal.
- Adjusted relative amplitudes to balance the different sound layers.
- Aligned audio array lengths to avoid processing errors.
- Applied peak normalization to reduce clipping.

## Development Process

The project was developed through several stages:

1. Studied basic waveform generation and audio playback using Python.
2. Explored the rhythmic and sonic characteristics of Psy Trance.
3. Designed the basic musical structure using Logic Pro.
4. Implemented Kick, Bass, and Lead synthesis in Python.
5. Debugged array indexing, envelope application, and signal mixing.
6. Combined the synthesized elements into a repeating electronic music sequence.

## Challenges and Learning Outcomes

One of the main challenges was understanding how musical timing and audio signals could be represented numerically.

During development, I encountered issues involving array indexing, envelope application, signal lengths, and amplitude balancing.

Resolving these issues helped me develop a better understanding of:

- Digital audio representation and sampling
- Waveform synthesis and amplitude envelopes
- Rhythm generation through numerical operations
- Audio signal mixing and normalization
- The relationship between musical structure and programming logic

This project also helped me connect my background in electronic music production with fundamental concepts in audio programming.

## Project Files

- [Python Source Code (Jupyter Notebook)](psytrance_synthesis.ipynb)
- [Development Report (Japanese)](Development_Report.pdf)

## Future Improvements

- Implement LFO-based modulation and digital filters.
- Expand the range of synthesized sounds and rhythmic patterns.
- Refactor the code into reusable functions.
- Introduce interactive parameter control.
- Explore real-time sound generation and live coding workflows.

## About This Project

This project was developed as part of my coursework at Tokyo College of Music, Music Business and Technology (MBT).

It represents an early exploration of the intersection between **music production, digital signal processing, and creative coding**.
