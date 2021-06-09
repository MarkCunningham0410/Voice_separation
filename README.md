# Voice_separation
Algorithm separating Vocal/Musical components of a song.

Based on MUSIC/VOICE SEPARATION USING THE 2D FOURIER TRANSFORM - by - Prem Seetharaman, Fatemeh Pishdadian, Bryan Pard.

Program takes .wav file as input. Outputs bg.wav and fg.wav.

### Tuneable Parameters 
nperseg - Number of frequency bins in STFT to produce spectrogram

w - window size for detecting peaks in 2DFT spectrogram

k - Peak sensitivity; Number of standard deviations within window to determine peak
