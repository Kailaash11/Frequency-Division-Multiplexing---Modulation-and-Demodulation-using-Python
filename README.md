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

![WhatsApp Image 2026-04-09 at 8 56 07 AM](https://github.com/user-attachments/assets/c0ca4cd7-5782-4db8-bfdf-f1bb5498eb3d)

![WhatsApp Image 2026-04-09 at 8 57 05 AM](https://github.com/user-attachments/assets/fbe7631f-1f6a-4980-adce-02e5f47f9b3d)

![WhatsApp Image 2026-04-09 at 8 57 23 AM](https://github.com/user-attachments/assets/8617a523-e411-4ce1-ac40-3780b19c2444)

__Tabulation__

![WhatsApp Image 2026-04-09 at 8 56 38 AM](https://github.com/user-attachments/assets/3438937f-bc9c-4916-b0f3-91d47f65052e)






__Output__:

![WhatsApp Image 2026-04-09 at 8 55 47 AM](https://github.com/user-attachments/assets/d53f597e-6e3f-46bd-bbf7-2a8321a66b30)
<img width="1600" height="778" alt="image" src="https://github.com/user-attachments/assets/e14d2290-c709-46b4-af91-2ca70052e16f" />





__Result__:

![WhatsApp Image 2026-04-09 at 8 57 31 AM](https://github.com/user-attachments/assets/4cda1ab3-ac7f-4b5d-ac73-d82c8177dcdd)


