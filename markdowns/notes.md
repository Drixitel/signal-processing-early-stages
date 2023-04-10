# Outline/Notes/General Discussion

Digital Signal:

- Discrete
- represented by sequence of discrete values

Analog Signal:

- Continuous
- Analog signals are digitized and analyzed
  - signals from microphones
  - radio signals from radio receivers
  - voltage signals from photomultiplier tubes
- susceptible to noise

Analog to Digital:

- covert by sampling the analog signal at evenly spaced time intervals which are determined by the sampling rate

Sample rate $(f_s)$:

- is sample frequency
- 10Hz = 10 samples / 1 sec

Acuate Recreation of Analog to Digital: `Lai`

- Condition: Nyquist Criterion
  $$
  f_s \geq 2\omega
  $$
- Where $\omega$ is the largest frequency of the analog signal

Noise:

- Analog signals are susceptible to noise
- by extension analog-sampled digital signals are too
- Sources:
  - electrical interference
  - thermal

Filters the old solution to noise `Taylor`

- Analog signals required real filters
- electronic devices (filters)
  - resistors
  - capacitors
  - inductors?
  - real limitations at very hi or very low frequencies
- Digital Filter: FFT and DFT
  - computer algorithm replacement for physical filters

Fast Fourier Transform Algorithm

- mathematical theorem based in continuous functions aka analog
- decomposes a signal in time into it's frequency components
- from a signal in the time domain into one in the frequency domain

Uses in Physics:

- EM waves
  - wave packets to fundamental wave constitutes
- Quantum Mechanical Waves
  - spacial domain to momentum domain

Removing noise & Techniques

- input: digital signals
- filter: digital signals
- Need: digital analogue of a FT aka DFT
- Techniques in noise reduction
  - autocorrelation
    - relies on non-correlation of noise over long time periods
  - Windowed-sinc filter
    - analogue to a band filter
    - works on convolution
  - both have efficiency limitations which depend on the severity of the noise

# DFT `Landau`

- truncate the integral to the length of a period
- reduce the infinite sum to a finite sum using trapezoid numerical integration

# Correlation function

# Autocorrelation function

- the correlation with itself

# Power spectrum of a signal
