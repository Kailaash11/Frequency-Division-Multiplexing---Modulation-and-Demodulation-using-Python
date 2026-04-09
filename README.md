# Frequency-Division-Multiplexing---Modulation-and-Demodulation-using-Python

__Aim__:

To generate an FDM signal by multiplexing multiple baseband message signals on different carrier frequencies, transmit (sum) them, optionally add channel noise, then recover each message by bandpass filtering and coherent demodulation in Python (Google Colab). Observe time & frequency domain signals and measure recovery quality.


__Apparatus Required__:

Google Colab (or any Python environment)

Python libraries: numpy, matplotlib, scipy (scipy.signal)


__Theory__:

FDM places different message signals in separate, non-overlapping frequency bands by modulating each message onto a distinct carrier frequency. The multiplexed signal is the sum of all modulated channels. At the receiver, bandpass filters (or tuned filters) isolate each channel; then each isolated carrier is demodulated (coherently multiplied by a synchronized carrier) and low-pass filtered to recover the original baseband.

__Procedure__:

1 — Imports and parameters

2 — Create message signals and carriers

3 — Modulate each message (standard AM DSB-SC) and form FDM signal

4 — Frequency domain (spectrum) of FDM signal

5 — (Optional) Add AWGN noise to FDM signal

6 — Receiver: isolate each channel with bandpass filter

7 — Demodulate each isolated channel (coherent) and low-pass filter to recover baseband
__Program__:
<img width="1558" height="1600" alt="image" src="https://github.com/user-attachments/assets/50d61dde-b2b0-4947-b856-827ca30cb067" />

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/383d01e3-7bc4-4f30-a975-df4288bfe7f2" />



__Output__:

![WhatsApp Image 2026-04-09 at 8 39 34 AM](https://github.com/user-attachments/assets/0de7a540-b675-483b-a7a5-a3a0fe4345b9)


__Result__:

![WhatsApp Image 2026-04-09 at 8 42 20 AM](https://github.com/user-attachments/assets/81aede00-3ed6-410b-9970-055090254cc4)

