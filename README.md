Almost complete schematics for complex dual analog oscillator in tradition of Buchla 258/259 with redesign from first principles for the digital age. For non-commercial use only.

Modulation oscillator is a self stablizing sine wave based around a trig identity.

Output oscillator is a variable harmonic wavetable implemented using Legendre's Ordinary Differential Equation, which generates polynomial functions in a completely novel and often frustrating way. Legendre polynomials are similar to Chebyshev.

The stabilization technique in this oscillator is also state of the art, although there is a comprmise between harmonic distortion and ampltiude distortion. Ampltitude distortion as the RMS to DC converter gets stuck in a modulation loop is probably the more destructive force here for audio work. It can be mitigated by avoid rapid changes in oscillator frequency, perhaps by using a slew limiter.

Output oscillator uses four quadrant multipliers and is designed for through zero behaviour.
