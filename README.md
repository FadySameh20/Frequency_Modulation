# Frequency_Modulation
Implementing frequency modulation by generating a frequency modulated narrow band (NBFM) signal. Moreover, detection can be done using a differentiator and an envelope detector (ED).

* Procedures:
1. Use Matlab to read the attached audio file, which has a sampling frequency Fs= 48 KHz. Find the spectrum of this signal (the signal in frequency domain). [audioread, fft , fftshift , plot]
2. Using an ideal Filter, remove all frequencies greater than 4 KHz.
3. Obtain the filtered signal in time domain and frequency domain, this is a band limited signal of BW=4KHz. [ifftshift ,ifft]
4. Sound the filtered audio signal (make sure that there is only a small error in the filtered signal) [sound]
5. Generate the NBFM signal. Use a carrier frequency of 100kHz and a sampling frequency of 𝐹𝑠 = 5𝐹𝑐 . Plot the resulting spectrum. What can you make out of the resulting plot?
6.what is the condition we needed to achieve NBFM.
7. Demodulate the NBFM signal using a differentiator and an ED. For the differentiator, you can use the following command: diff. Assume no noise is introduced.
