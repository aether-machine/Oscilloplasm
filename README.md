Almost complete schematics for complex dual analog oscillator in tradition of Buchla 258/259 with redesign from first principles for the digital age. For non-commercial use only, e.g. education, DIY.
Modulation oscillator is a self stablizing sine wave based around a trig identity for in the loop gain correction. Basic sine wave (harmonic oscillator) equation is:

$$
\frac{d^2x}{dt^2} + \omega^2 x = 0
$$

Where the second differential x'' (with respect to time) is passed through two voltage controlled integrators, with the inversion of the x output connected to the input to solve. The complete equation with stabilization is:

$$ \lambda^2 - 2k \epsilon \lambda + (\omega^2 + k^2 \epsilon^2) = 0 $$


Output oscillator is a variable harmonic wavetable that solves Legendre's Ordinary Differential Equation in real time:

$$
(1 - t^2) \frac{d^2x}{dt^2} - 2t \omega \frac{dx}{dt} + (\omega^2 - l(l+1))x = 0
$$


Thus generating polynomial functions in a completely novel (and sometimes frustrating) way, where L represents the azimuthal quantum number.

The stabilization technique in this oscillator is also state of the art, although there is a comprmise between harmonic distortion and ampltiude distortion. Ampltitude distortion as the RMS to DC converter gets stuck in a modulation loop is probably the more destructive force here for audio work. It can be mitigated by avoid rapid changes in oscillator frequency, perhaps by using a slew limiter.

Output oscillator uses four quadrant multipliers and is designed for through zero behaviour.
