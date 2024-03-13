# Introduction

**Name:** Zhihao Wang  
**Assignment:** aleatoric

## Purpose

This program continuously plays music measures (never stopping), with each measure consisting of 8 beats. The first beat is the root note of the minor scale, and the remaining 7 beats are tones randomly selected from notes 2 to 8 of the A4 (natural) minor scale. Each measure is played at a tempo of 220 beats per minute, with the root note's volume set at -3 dBFS and the rest at -6 dBFS. The program will save the first two measures to the current directory.

### How to Run

Please make sure the numpy, scipy, sounddevice Libraries are installed before running

To run the program, use the following command in your terminal:

```bash
python aleatoric.py
