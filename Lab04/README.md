# Lab 04 — Intermediate-Frequency Amplifiers

I built and tested the two KSP10 transistor stages of the TRC-11 intermediate-frequency amplifier. I measured each stage separately at **15.003 MHz** before connecting them through coupling capacitor C52.

## Stage measurements

| Stage | Input (peak-to-peak) | Output (peak-to-peak) | Voltage gain |
| --- | ---: | ---: | ---: |
| First (TP50 → TP51) | 92.0 mV | 5.20 V | 35.04 dB |
| Second (TP60 → TP61) | 92.8 mV | 5.60 V | 35.61 dB |

The first stage measured 4.22 dB above its simulated gain of 30.82 dB. Both stages produced similar gains under the same test conditions.

[Read the full lab report (PDF)](../LabReport4_final.pdf)
