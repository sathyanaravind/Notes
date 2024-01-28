## Deep Learning for Audio

#### Sound
produced by vibrations of objects

#### Waveform
- frequency = pitch
- amplitude = loudness
  
#### Analog Digital Conversion
- signal sampled at uniform time intervals
- amplitude quantized with limited no of bits
- sample rate = 44,100 Hz
- Bit depth = 16 bits/ channel
  
#### Fourier Transform
- Decompose complex periodic sound into sum of sine waves oscillating at different frequencies
- we can now understand how different frequencies contribute to the original wave
- from time to frequency domain
- no time information
- gives a power spectrum
- ![image](https://github.com/sathyanaravind/Notes/assets/77285092/377987c7-803f-403c-881f-5214f50e5bf4)

#### Short Term FT
- computes several FFTS at different intervals
- preserves times information
- fixed rate size (eg: 2048 samples)
- gives a spectrogram(time +frquency+ magnitude )
![image](https://github.com/sathyanaravind/Notes/assets/77285092/5b3b3efc-5ad5-42c2-8727-163f0bf61b4b)

#### DL Pipleline for Audio data
![image](https://github.com/sathyanaravind/Notes/assets/77285092/fb72ca09-30f6-4e78-9d4d-f874bef84cfc)

#### Mel Spectrum
- capture timbral/textural aspects of sound
- frequency domain
- approximate human auditory system
- 13 to 40 coefficients
- calculated at each frame
