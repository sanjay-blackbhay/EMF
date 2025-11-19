# EMF
Rectangular and Circular Cavity Resonators
1. Introduction
The allowed field patterns depend on cavity geometry.
A cavity resonator is a closed conducting structure that stores electromagnetic
energy by supporting standing waves at specific resonant frequencies.
When a waveguide is closed at both ends, it forms a cavity that supports only
discrete field patterns called modes.
These cavity resonators are widely used in:
Microwave filters
Oscillators
Radar systems
Particle accelerators
Two commonly used cavity geometries are:
Rectangular cavity resonator
Circular (cylindrical) cavity resonator
<img width="391" height="430" alt="image" src="https://github.com/user-attachments/assets/d683b890-c956-412e-aa7b-0ada1021aa15" />
2. Field Modes
In both types of resonators, the electromagnetic fields satisfy:
Maxwell’s equations
Boundary condition:
Tangential electric field = 0 on conducting walls
Two main types of field patterns exist:
Mode TypeCondition
TE (Transverse Electric)
Ez=0E
_
z = 0Ez=0, but Hz≠0H
_
z \neq 0Hz=0
TM (Transverse Magnetic)
Hz=0H
_
z = 0Hz=0, but Ez≠0E
_
z \neq 0Ez=0
The allowed field patterns depend on cavity geometry.
3. Field Modes in Rectangular Cavity
3.1 Geometry
Let the cavity have dimensions:
Length along x → a
Width along y → b
Height along z → d
3.3 Mode Characteristics
Field variations are sinusoidal along x, y, and z.
The mode with minimum resonant frequency is called the dominant mode.
Common dominant modes: TE₁₀₁, TE₁₀₀ (depends on dimensions)
<img width="672" height="411" alt="image" src="https://github.com/user-attachments/assets/e138a403-fd9e-4c30-ae67-c3e749d8ccdd" />
4. Resonant Frequency of Rectangular Cavity
The reflection coefficient expresses the portion of the incident signal reflected back
from the load. On the Smith Chart, its magnitude directly corresponds to the radial
distance from the center of the chart to the plotted impedance point. This graphical
method makes analysis faster and prevents calculation errors during design.
A low reflection coefficient indicates good matching, while a high value suggests major
mismatch and potential distortion in RF circuits. Engineers rely on this parameter to
assess the reliability of wireless communication links and determine necessary
corrective actions.
5. Q-Factor and Losses:
The quality factor (Q) of a cavity resonator represents how well it stores energy:
Q=2π×Energy storedEnergy lost per cycleQ = 2\pi \times \frac{\text{Energy stored}}
{\text{Energy lost per cycle}}Q=2π×Energy lost per cycleEnergy storedHigh Q →
narrow bandwidth, low loss, very selective resonance
Losses occur due to:
Finite conductivity of metal walls (ohmic loss)
Dielectric loss (if filled with dielectric)
Radiation loss (if there are coupling holes/slots)
<img width="780" height="407" alt="image" src="https://github.com/user-attachments/assets/64769d70-0e4e-4f9d-af27-ed2d0d81563d" />
6. Real-Time Example
<img width="717" height="260" alt="image" src="https://github.com/user-attachments/assets/237fbc66-dd1e-429a-9b9e-df3ab9c349ae" />
7. Conclusion
Rectangular cavity resonators are basic but powerful components in microwave
engineering.
They support discrete TE and TM modes determined by the cavity dimensions and
material.
Their high Q-factor, mechanical stability, and frequency selectivity make them ideal for
use in high-frequency filters, oscillators, and radar systems.
<img width="677" height="735" alt="image" src="https://github.com/user-attachments/assets/514c36ff-25c3-41ad-8094-b06105a70fab" />
References
1.Pozar, D. M., Microwave Engineering, Wiley.
2.Ramo, Whinnery & Van Duzer, Fields and Waves in Communication Electronics.
3.Collin, R. E., Foundations for Microwave Engineering.
