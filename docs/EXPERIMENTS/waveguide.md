# Waveguide 📡📶

# OVERVIEW 🔍

- The purpose of this laboratory exercise is to familiarize ourselves with the fundamental components of a microwave test bench. In our theoretical lectures, we learned that microwave signals, specifically those in the X-band, which ranges from 8.2 to 12.4 GHz, behave very differently than lower - frequency electrical signals. At these high frequencies, standard wires and coaxial cables experience severe power loss, radiation, and skin effect issues. To overcome this, microwave circuits use waveguides: hollow, rectangular metal tubes specifically dimensioned to guide the electromagnetic waves efficiently from one point to another.

# OBJECTIVES 📝

The main focus of this lab experiment is to gain a practical understanding of the X-band microwave test bench through the following objectives:

- Equipment Identification: To correctly identify each component within the provided training kits, ranging from the electronic power units to the various passive waveguide sections.

- Functional Understanding of Active Sources: To learn how the Gunn Oscillator Power Supply and Gunn Diode Mount work together to generate microwave signals, and how the 1 kHz Generator is used for signal modulation.

- Mastery of Waveguide Assembly: To become familiar with the mechanical requirements of a microwave circuit, including the proper use of waveguide stands for alignment and assembly hardware to ensure leak-proof flange connections.

- Study of Signal Manipulation: To understand the practical use of the Variable Attenuator for power control and the Slide Screw Tuner for adjusting impedance and reflections within the system.

- Practical Measurement Techniques: To familiarize ourselves with the Slotted Line Section and its tunable probe to understand how standing waves are physically sampled and measured.

-  Characterization of Terminations and Radiators: To distinguish between the uses of Matched Terminations (for absorbing energy), Short Circuits (for reflecting energy), and Horn Antennas (for transmitting energy into free space).

# Material and Component Used ⚙️
- 1 kHz Square Wave Generator
- Gunn Oscillator Power Supply (U-3000P)
- Gunn Diode Mount / Oscillator
- Slotted Line Section with Tunable Probe
- Variable Attenuator (Rotary Dial)
- Directional Coupler
- Slide Screw Tuner
- Pyramidal Horn Antennas
- Variable Short Circuit (Micrometer Type)
- E-Plane and H-Plane Waveguide Tees
- Straight Waveguide Sections
- Matched Terminations / Loads
- Solid Short-Circuit Plates
- Waveguide Stands
- Waveguide Assembly Hardware (Thumbscrews and Alignment Pins)

# SUMMARY OF FINDINGS AND RESULTS 🔬

![equipment](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f8324c6dbc6d36fa2146e8468170ea963ba9a28f/docs/documentation/Screenshot%202026-03-01%20125701.png)

# 1 kHz Square Wave Generator 📌
- The 1 kHz square wave generator is a control unit used to modulate our continuous microwave signal. By applying this low-frequency modulation to our microwave source, we allow standard SWR (Standing Wave Ratio) meters and oscilloscopes downstream to easily detect and read the signal, which would otherwise be too high-frequency for our basic bench instruments to process directly.
   
# Waveguide Stands 📌
- Waveguide stands are crucial mechanical supports for our entire test bench layout. Because the brass and aluminum waveguide components are heavy and rigid, these adjustable stands ensure the assembly remains perfectly level and aligned on the lab bench, which prevents physical stress on the delicate flange joints and minimizes signal leakage.
  
# Gunn Oscillator Power Supply 📌
- The Gunn oscillator power supply (model U-3000P) acts as the primary power source for our active components. It provides the necessary DC bias voltage to drive the Gunn diode into oscillation. By carefully adjusting the voltage dial on this unit, we can make minor adjustments to the output power and ensure the diode is operating in its proper negative resistance region.

# Waveguide/Termination Flanges 📌
- The waveguide and termination flanges are the flat, square, or rectangular metal plates located at the bottom center of the first equipment case. These components serve as the critical interface between different sections of the microwave bench. While some are simply "Plain Flanges" used to extend a connection, the ones with a solid metal backing are "Shorting Plates" or "Fixed Terminations". They are designed to be bolted onto the end of a waveguide run using the provided assembly hardware to either completely reflect the signal back (short circuit) or provide a fixed point of measurement for impedance studies. Without these flanges, the microwave energy would simply radiate out of the open end of the waveguide, causing power loss and potential interference.

![equipment2](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/26c7e6c96f3d72ccea00abacf88dc6e1aeb0c11b/docs/documentation/Screenshot%202026-03-01%20131359.png)

# Slotted Line Section with Tunable Probe 📌
- The slotted line section is our primary measurement tool for analyzing standing waves. It is a length of waveguide with a narrow longitudinal slot cut into its top broad wall, allowing a sliding carriage with a small antenna probe to dip inside. By moving this probe along the slot, we can sample the electric field amplitude at various points to find the minimum and maximum voltage nodes, allowing us to calculate the system's VSWR.

# Waveguide Tees (E-Plane and H-Plane) 📌
- Waveguide tees act as splitters or combiners for our microwave circuits. An E-plane tee splits an incoming signal into two out-of-phase signals, while an H-plane tee splits it into two in-phase signals. These three-port junctions are fundamental building blocks for creating more complex routing paths, such as interferometers or balanced mixers, on our test bench.

# Gunn Diode Mount / Oscillator 📌
- The Gunn diode mount serves as our actual microwave signal generator. It consists of a resonant cavity housing the Gunn diode itself, along with a mechanical tuning micrometer. When powered by the external supply, the diode generates X-band microwaves, and we can manually turn the micrometer to change the physical dimensions of the cavity, thereby fine-tuning our operating frequency.

# Straight Waveguide Sections 📌
- The straight waveguide sections are simple, hollow rectangular metal tubes used as basic transmission lines. They do not alter the signal's properties but are necessary to physically connect different components together, allowing us to build the physical layout of our test bench and properly space out items like the source, attenuators, and slotted lines.

# Directional Coupler 📌
- The directional coupler allows us to safely monitor the microwave signal without interrupting the main power flow of our experiment. It consists of a primary waveguide and a secondary branching arm connected by small, precisely machined holes. These holes are designed to sample only a small, known fraction of the microwave power traveling in the forward direction, routing it to a separate port for measurement while ignoring any reflected power traveling backward.

# Matched Terminations and Solid Shorts 📌
- Matched terminations and solid shorts are used to cap off the ends of our waveguide runs, but they serve entirely opposite purposes. A matched termination contains a tapered piece of absorptive material that completely soaks up the incoming microwave energy, preventing any reflection back into the system. Conversely, a solid short is a flat metal plate that intentionally reflects 100% of the energy back toward the source, which we use specifically to set up strong standing waves for measurement.

# Variable Attenuator 📌
- The variable attenuator is used to control the power level of the microwave signal traveling through our circuit. It features a large rotary dial that lowers a resistive card (a lossy material) deeper into the waveguide to absorb some of the energy without changing the signal's frequency. This is essential for protecting sensitive detectors from power overloads and for isolating our source from reflections further down the line.

# Slide Screw Tuner 📌
- The slide screw tuner is an impedance matching device used to eliminate unwanted reflections in our system. Similar in appearance to the slotted line, it features a sliding carriage, but instead of a measuring probe, it contains a metallic post that lowers into the waveguide. By adjusting both the depth of this post and its position along the waveguide, we can introduce a controlled reflection that perfectly cancels out an existing mismatched load.

#  Pyramidal Horn Antennas 📌
- The pyramidal horn antennas are flared waveguide sections used to transition our guided microwave signals into free space. In our lab, we will use these in pairs—one as a transmitter and one as a receiver—to conduct experiments on radiation patterns, antenna gain, and free-space wave propagation. The flared shape helps match the impedance of the waveguide to the impedance of free air, minimizing reflections at the opening.

# Variable Short Circuit 📌 
- The variable short circuit is a highly precise reflecting component fitted with a micrometer barrel. While a standard solid short simply caps the waveguide to bounce the signal back, the variable short allows us to physically move the exact position of that short-circuit plane inward or outward. This mechanical adjustment lets us perfectly shift the phase of our standing wave, which is very useful for complex impedance matching and calibration tasks.

# Reflection/Learning Summary 💡

-  Completing this equipment familiarization has been a crucial first step in moving from theoretical microwave concepts to actual laboratory practice. One of the most significant things I learned is that working at X-band frequencies (8.2 to 12.4 GHz) requires a completely different mechanical mindset compared to standard electronics. In previous labs, we used flexible wires, but here, the "circuit" is a rigid mechanical assembly. I now understand that the Waveguide Stands and Assembly Hardware aren't just accessories—they are vital for ensuring that the rectangular pipe dimensions remain perfectly consistent across joints to prevent signal leakage.

- I also found it interesting how we "see" the microwave signal. Since we can't measure GHz-level frequencies with a standard multimeter, learning about the 1 kHz Square Wave Generator and the Slotted Line Section was eye-opening. It’s clever how we modulate the signal just so we can detect it, and how the physical movement of a probe along a slot allows us to "map out" invisible electromagnetic waves. Seeing the difference between a Matched Termination (which "tricks" the wave into thinking the pipe goes on forever) and a Short Circuit (which forces it to bounce back) really helped clarify the concept of standing waves.

- Ultimately, this session taught me that precision is everything in microwave engineering. From the fine-tuning of the Gunn Diode Mount to the delicate adjustments of the Variable Attenuator, every component must be handled with care. I feel much more confident now about our upcoming experiments because I can identify the hardware by sight and understand exactly what role each piece plays in controlling the flow of microwave energy.
