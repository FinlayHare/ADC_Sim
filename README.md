# ADC_Sim
Analog Signal to Digital Bitstream: A Simple MATLAB Simulation

Signal Generation: We start by creating a smooth sine wave representing a continuous-time analog signal at 100 Hz. We cannot make an analogue signal, but we can mimic it by having a very small time step.

Sampling: The analog signal is sampled at 1 kHz, capturing discrete points in time while respecting the Nyquist criterion.

Quantization: These sampled amplitudes are then rounded to one of 16 levels (4-bit resolution), simulating the finite precision of digital systems.

Encoding: Each quantized level is converted into a 4-bit binary code.

Digital Bitstream: Finally, these binary codes are concatenated to produce a stream of bits representing the original analog signal digitally.
