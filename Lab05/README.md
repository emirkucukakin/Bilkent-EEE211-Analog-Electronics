# Lab 05 — Tuned RF Transmitter Amplifier

I investigated the TRC-11 transmitter stage, which uses a 2N2222 transistor and a tuned output transformer. I used the oscilloscope FFT to compare the harmonics with the **27.002 MHz** fundamental at two input amplitudes.

## Harmonic measurements

The table gives the number of decibels by which each harmonic fell below the fundamental.

| Harmonic | 7 V peak-to-peak input | 3.5 V peak-to-peak input |
| --- | ---: | ---: |
| Second (54.004 MHz) | 19.6 dB | 22.8 dB |
| Third (81.006 MHz) | 29.6 dB | 38.8 dB |

Halving the input amplitude increased the separation from the fundamental by **3.2 dB** for the second harmonic and **9.2 dB** for the third.

[Read the full lab report (PDF)](../LabReport5_final.pdf)
