# ANTENNA TRAINER 📡📶🛰️📻

# OVERVIEW 🔍
- The study of telecommunications heavily relies on the efficient transmission and reception of radio frequency (RF) signals, making antennas a fundamental component of any wireless system. At its core, an antenna functions as a crucial transducer; it converts alternating electrical currents from a transmitter into propagating electromagnetic waves in free space, and performs the reverse process at the receiver. In this laboratory experiment, our primary objective was to practically observe, examine, and understand the physical and electrical characteristics of various foundational antenna designs.

-  To achieve this, we utilized a specialized educational antenna trainer kit. This equipment features a centralized RF signal generator and a diverse set of interchangeable, modular antennas built onto green printed circuit boards (PCBs). By physically handling and swapping these modules—ranging from simple elemental designs like the half-wave dipole to more complex, multi-element arrays like the Yagi-Uda and Log-Periodic—we were able to directly correlate theoretical classroom concepts with practical geometries. This hands-on approach provided a foundational understanding of how specific structural modifications, such as adding parasitic elements or altering conductive trace shapes, directly influence key performance parameters like radiation patterns, directivity, bandwidth, and impedance matching.

# OBJECTIVES 📝
-  Identify and Classify Antenna Topologies: To physically examine and differentiate between a wide variety of standard antenna designs—including Hertz (simple dipole), folded dipoles, Yagi-Uda arrays, log-periodic antennas, loop, and rhombic configurations—using the provided modular printed circuit board (PCB) trainer kit.

- Analyze Radiation Patterns and Directivity: To understand how the physical structure and geometry of an antenna directly dictate its radiation pattern in free space. This involves comparing the relatively omnidirectional broadcasting pattern of a basic dipole with the highly focused, directional beams of Yagi-Uda designs, and the distinct bidirectional characteristics of loop antennas.

- Evaluate the Function of Parasitic Elements: To investigate how the addition of passive metal components—specifically reflectors and directors—interacts with a driven element. The goal is to observe how these parasitic elements constructively and destructively interfere with radio waves to increase overall forward gain and directivity, as seen in the 3-element and 5-element Yagi modules.

- Examine Impedance and Bandwidth Characteristics: To explore how specific structural modifications alter an antenna's electrical properties. This includes understanding the four-fold impedance increase achieved by transitioning from a simple dipole to a folded dipole, and analyzing the ultra-wide bandwidth capabilities created by the progressively scaled geometry of the log-periodic antenna.

- Understand Array Interactions and Phasing: To study the principles of electromagnetic wave interference by examining the Phased Array module. The objective is to comprehend how driving multiple distinct elements simultaneously can shape a combined radiation pattern and allow for electronic beam steering.

# Material and Component Used ⚙️ 

# Primary Laboratory Equipment:

- Detector Module: A specialized receiving element used to pick up the transmitted RF signals and convert them into measurable readings, allowing us to map out the radiation patterns of the other antennas.

- Coaxial Cables (BNC): Standard laboratory RF cables used to connect the base kits to the signal generator and the measurement devices (implied by the connectors visible on the modules).
  
- RF Signal Generator / Transmitter Unit: The central base station used to generate the high-frequency alternating current required to drive the antennas.

- RF Receiver / Field Strength Meter: Used to detect and measure the relative strength of the radiated electromagnetic waves at various angles, allowing us to map out the radiation patterns of each antenna.

- Transmission Lines (Coaxial Cables/Twin-Lead): Used to connect the RF signal generator to the antenna modules, ensuring proper signal transfer with minimal loss.

- Antenna Mounting Mast / Rotating Stand: A structural support that holds the antenna modules and allows for precise 360-degree rotation during radiation pattern measurements.

  # Modular Antenna Boards (Green PCBs):

- Hertz Antenna (λ/2 Simple Dipole) Module: A basic straight cylindrical metal rod serving as the foundational half-wave radiating element.

- Folded Dipole (λ/2) Module: A dipole element bent into a continuous loop, utilized to observe higher input impedance (approx. 300 ohms) and wider bandwidth.

 - Antenna Kit "A" and "B" Modules: Base modules consisting of metallic pads and shorting plates used for impedance matching, calibration, or as mounting interfaces.

- Phase Array (λ/2) Module: A board featuring two parallel vertical dipoles used to demonstrate electronic beam steering and electromagnetic wave interference.

- 3-Element Yagi-Uda Module: Consists of a driven folded dipole, one reflector, and one director to demonstrate basic parasitic element interactions and increased forward gain.

- 5-Element Simple Yagi-Uda Module: A higher-gain array featuring a straight simple dipole driven element, one reflector, and three distinct directors.

- Log-Periodic Antenna Module: A geometrically scaled array of multiple parallel dipoles designed to demonstrate ultra-wide bandwidth capabilities.

- Loop Antenna Module: A continuous, square-shaped conductive trace etched onto the PCB, used to study magnetic field sensing and bidirectional radiation patterns.

- Rhombus (Rhombic) Antenna Module: A diamond-shaped conductive trace designed to demonstrate traveling-wave principles and highly directional, broadband performance.

# Directional and Array Antennas
  
- Yagi-Uda Simple 7 Elements & Yagi-Uda Folded Dipole 5 Element: Multi-element directional antennas consisting of a driven element, a reflector, and multiple directors used to demonstrate high-gain, narrowly focused beam transmissions.
  
- Broad Side Array: A multi-element circuit board module used to demonstrate how driving several antennas in phase creates a strong, flat signal perpendicular to the array.
  
- Phase Array λ/4 A grouping of quarter-wave elements used to observe signal shaping and steering through constructive and destructive interference.
  
- Combined Collinear Array: An end-to-end arrangement of elements used to demonstrate a flattened, horizontal radiation pattern ideal for ground-level communication.

# Basic and Omnidirectional Antennas

- Simple Dipole λ/2 and Simple Dipole λ/4: Basic straight-wire antennas cut to half and quarter wavelengths, used to demonstrate fundamental omnidirectional radiation patterns.
  
- Simple Dipole 3λ2: A longer standard dipole used to observe how extending the physical length past a single wavelength alters the basic donut-shaped radiation pattern into multiple lobes.
  
- Folded Dipole λ/2: A modified half-wave dipole with a continuous closed loop, used to demonstrate increased impedance and wider bandwidth.
  
- Ground Plane: A flat, metallic base module used in conjunction with vertical antennas to simulate a flat earth reflection, essentially doubling the antenna's efficiency.

# SUMMARY OF FINDINGS AND RESULTS 🔬

# Log-Periodic Antenna 📡
![log periodic antenna](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/637293864_1442700864319134_3535019229065035810_n%20(1).jpg)

- This was visually the most complex module, featuring multiple pairs of straight dipoles arranged sequentially on the PCB, progressively increasing in length from the front to the back. What makes this design so clever is its geometry; it's essentially a series of parallel dipoles where only one or two pairs are electrically resonant at any given frequency. As the signal frequency changes, the "active" radiating region simply shifts along the length of the antenna.  This gives the log-periodic antenna an incredibly wide bandwidth, allowing it to operate across multiple frequency bands while maintaining a relatively consistent directional radiation pattern and impedance.

# Loop Antenna 📡
![loop antenna](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/637230196_1393097625462736_5288885748834978646_n.jpg)

- Instead of metal rods, this module uses a continuous square-shaped conductive trace etched directly onto the green PCB. Because the dimensions of the loop are relatively small compared to the wavelength, it primarily operates by sensing the magnetic component of an incoming electromagnetic field rather than the electrical component. This results in a classic "figure-8" radiation pattern. From our lab manual, I noted that these are highly directional and are excellent at rejecting noise, making them very popular for direction-finding applications and AM radio receivers.

# The Hertz Antenna (Simple Dipole) 📡
![hertz antenna](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/639484746_906418728788463_4698009589084317337_n.jpg)

- The Hertz antenna module we examined consists of a simple straight cylindrical metal rod connected directly to the feed block. In theory, this represents the foundational half-wave dipole (λ/2) antenna. When an alternating current is applied, the two halves of the rod act as a resonator, radiating electromagnetic waves outward. I noted that this is the most basic building block for many complex antennas. It typically has an omnidirectional radiation pattern in the plane perpendicular to the rod, shaped like a donut, giving it moderate gain and making it ideal for general broadcasting where a signal needs to reach multiple directions.

# Rhombus (Rhombic) Antenna 📡
![rhombus antenna](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/641171864_940162801874863_2331004682275103922_n.jpg)

- Similar to the loop antenna, this module consists of traces on the PCB, but shaped into a diamond or rhombus. Typically, a true rhombic antenna is a traveling-wave antenna that is terminated with a resistor at the far end, which absorbs any un-radiated power and prevents standing waves. This results in an antenna that is highly directional (radiating towards the terminated end) and has a very broad bandwidth.  Seeing it scaled down on a PCB helps visualize how the physical geometry of the traces dictates the phase of the current traveling along the wires, shaping the final directional beam.

# 5-Element Simple Yagi-Uda 📡
![5 element](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/625065639_1634544421297192_8398203100956769742_n.jpg)

- Building on the principles of the 3-element version, this module uses a standard straight simple dipole as its driven element instead of a folded one. It features one reflector at the back and three directors in the front, arranged from longest to shortest. By adding more directors, the antenna focuses the electromagnetic energy into an even narrower and more powerful forward beam. This significantly increases the antenna's overall gain and range, making it the classic design used for long-distance rooftop television antennas where capturing a weak, distant signal is necessary.

# 3-Element Yagi-Uda (with Folded Dipole) 📡
![3 element](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/637490976_1416003569511873_4211439107406462378_n.jpg)

- This antenna module introduces parasitic elements to increase directivity. It consists of three parts: a folded dipole in the middle acting as the "driven" element (where the actual power is applied), a slightly longer metal rod behind it acting as a "reflector," and a shorter metal rod in front acting as a "director." The reflector blocks the radio waves from going backward and bounces them forward, while the director focuses the waves into a tighter beam at the front. This combination gives the Yagi-Uda a highly directional radiation pattern with excellent forward gain.

# Phase Array λ/2 Antenna 📡
![phase array](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/641041673_1220953120230709_6574345837916988867_n.jpg)

- This module was particularly interesting because it features two separate vertical dipole elements mounted on the same green PCB. By feeding both elements with a signal, their individual radiated waves interact with each other. Depending on the electrical phase difference of the signal reaching each element—which can be controlled by the trace lines on the PCB—the waves will either constructively interfere to boost the signal in a specific direction or destructively interfere to cancel it out.  This means we can essentially "steer" the main beam of the antenna electronically without physically moving it, a principle heavily used in modern 5G networks and radar systems.

#  Antenna Kit "A" and "B" Modules 🛠️
![A](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/643769240_25182395098032728_6337143550631439460_n.jpg)
![B](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/643772825_1277158364359341_934803033334528514_n.jpg)

- We also examined two distinct base modules labeled "Antenna Kit 'A'" and "Antenna Kit 'B'". These modules do not have long radiating metal elements attached to them. Instead, Kit 'A' features two distinct metal pads at the bottom of the PCB, while Kit 'B' appears to have a continuous solid metal block or shorting plate. In the context of our lab trainer, these act as the foundational mounting bases, impedance matching networks, or calibration tools (like open/short loads) that allow us to properly interface the signal generator's transmission line with the various radiating elements without experiencing massive signal reflection.

# The Folded Dipole (λ/2) Antenna 📡
![folded](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/641783063_1336658681546841_690842262920423867_n.jpg)

- Unlike the simple straight rod of the Hertz antenna, this module features a metal element that is bent back onto itself, forming a continuous loop where the ends meet at the feed point. From our textbook discussions, I know that folding the dipole like this significantly changes its electrical characteristics. Most notably, it quadruples the input impedance from roughly 73 ohms (in a standard dipole) to about 300 ohms. This makes it much easier to match with standard twin-lead transmission lines. Additionally, I learned that the folded design gives this antenna a wider bandwidth compared to a standard straight dipole, making it very useful in television and FM radio reception.

# Broad Side Array 🛠️
![broad](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/639702158_926461899835898_586625110016241957_n.jpg)

- The broadside array is another grouping of multiple antenna elements, but it is specifically arranged to push its strongest signal completely flat and perpendicular to the board itself. By feeding all the elements the same signal in phase, the radio waves add up constructively to create a massive wall of energy shooting straight out from the flat side of the array. It’s a really clever way to concentrate a signal over a wide area without needing a curved dish.

# Yagi-Uda Simple 7 Elements 📡
![7 elemment](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/642527465_1196529049224268_4094142700518234006_n.jpg)

- Unlike the simple dipoles that scatter signals everywhere, this Yagi-Uda antenna is highly directional. It uses one main driven element connected to the power, a slightly longer "reflector" rod right behind it, and five shorter "director" rods lined up in front. The reflector bounces the signal forward, while the directors pull and focus the wave into a tight, narrow beam. It acts exactly like a flashlight for radio waves, making it perfect for pointing directly at a distant target to get a strong, clear signal without interference from the sides.

# Paraboloid / Simple Dipole 📡
![paraboloid](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/638749737_674959672341679_7927880378554278547_n.jpg)

This specific block is designed to act as the central "feed" element for a larger parabolic dish (like a satellite dish). On its own, it just acts like a small antenna, but its real job is to sit at the exact focal point of a curved reflector. It either blasts its signal backward into the dish so it can be focused into a massive, straight beam into space, or it acts as the "catcher's mitt" to receive the faint signals that the giant dish gathers and bounces toward it.

# Phase Array λ/4 📡
![phase array](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/638084710_932323376154308_9185649791782105852_n.jpg)

- This module shows what happens when you arrange multiple antennas on a single circuit board to work together. Instead of just one rod, it has a grouping of quarter-wave elements. When these elements transmit their signals at the exact same time, their waves interact with each other in the air. They cancel out in some directions and combine to become much stronger in others, allowing us to steer or shape the signal beam without needing to physically move a large, bulky metal reflector.

# Simple Dipole λ/4 📡
![lambda/4](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/641310599_1404752914219829_7927460478691453088_n.jpg)

- Very similar to the half-wave version, this simple dipole is cut to a quarter of the signal's wavelength. It works on the exact same fundamental principles, acting as a basic omnidirectional radiator. We use different lengths like this in the kit to match different signal frequencies, since the physical size of the antenna has to perfectly resonate with the specific radio wave we are trying to transmit or receive to work efficiently.

# Simple Dipole λ/2 📡
![lambda/2](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/642527465_25877388318548885_2054583381162757655_n.jpg)

- This module is one of the most basic types of antennas we used in the lab. It consists of a straight metal rod cut exactly to half the wavelength of the signal it's designed to handle. In our experiments, we learned that it radiates energy outward in all directions perpendicular to the rod, creating a 360-degree shape that looks a lot like a donut. Because it sends and receives signals from almost anywhere around its sides, it's really useful for general broadcasting where you don't necessarily know exactly where the receiver is located.

# Simple Dipole 3λ/2 📡
![3λ/2](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/641049126_1251789490261907_1390679996207626631_n.jpg)

- This is just a much longer version of the simple dipoles we looked at before. Instead of being a half-wave (λ/2) or quarter-wave, this one is cut to be one-and-a-half times the wavelength (3λ/2) of the signal. Because it is physically much longer than the standard wave, its radiation pattern isn't a simple donut anymore. The extra length causes the radio waves to interact in a more complex way along the rod, splitting the signal into multiple distinct "lobes" or directional peaks. We use this in the lab to study how changing the physical length of an antenna dramatically alters the shape of the signal it throws into the air.

# Ground Plane 🛠️
![ground plane](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/637124681_1406650510780513_6913249892294965976_n.jpg)

- This square green board with metal strips extending outward is designed to act as an artificial "ground." When we place a simple vertical antenna (a monopole) right in the center connector, this flat board acts like a mirror, reflecting the radio waves. This tricks the vertical antenna into thinking it's sitting on an endlessly flat earth, effectively completing the circuit and doubling its efficiency. It's the exact same concept behind the radio antennas sticking up from the flat metal roof of a car.

# Slot Antenna 🛠️
![slot](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/641757866_1223874456525159_8591844377766017787_n.jpg)

- This one looks completely different from the metal rods! Instead of adding metal to transmit a signal, a slot antenna is made by taking a solid sheet of metal (or a copper-clad circuit board) and cutting a narrow gap (a slot) out of it. It works on a cool physics concept called "Babinet's principle," where the empty slot behaves electrically just like a solid metal dipole. These are incredibly useful when you need an antenna that sits completely flush against a flat surface, like on the nose of an airplane, where a protruding metal rod would cause too much wind resistance.

# Zeppline Antenna 📡
![zepp](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/641017762_918361550673304_8520599327946155522_n.jpg)

- The Zeppline (often called a Zepp) antenna gets its name from being used on early airships. Unlike a standard dipole where the coaxial cable connects right in the middle of two rods, the Zepp is an "end-fed" antenna, meaning the power is connected to one side. This design is really practical when you only have a single, long piece of wire to hang up and it’s not convenient to run a heavy feedline cable all the way to the center of it.

# Yagi-Uda Folded Dipole 5 Element 📡
![folded dipole 5 element](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/638074224_2171934900280234_8422577608052503294_n.jpg)

- This is another highly directional "flashlight" antenna, similar to the 7-element Yagi, but with a couple of key differences. First, it only has 5 elements (one reflector, the main driven element, and three directors). Second, the main element connected to the power is a folded dipole instead of a straight one. Using a folded dipole here gives the antenna a wider bandwidth, meaning it can pick up a broader range of frequencies clearly. This specific combination makes it an incredibly common design for standard rooftop TV antennas.

# Combined Collinear Array 🛠️
![combined](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/635531125_1608771770161730_6188902748114963413_n.jpg)

- This module arranges multiple antenna elements end-to-end in a straight line, which is exactly what "collinear" means. In our experiments, we learned that stacking elements this way squashes the radiation pattern down, making it much flatter. Instead of wasting energy shooting signals up into the ceiling or down into the floor, a collinear array pushes almost all of its energy out horizontally. It is a great design for communicating with receivers that are on the same ground level over a wide distance, much like a typical Wi-Fi router antenna.

# Detector 🛠️
![detect](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/f60960d187eca8237683b615ccd53aead6a527bc/docs/documentation/637455505_905587932095875_5374551658933683144_n.jpg)

- This module is a bit different from the standard transmitting antennas. In our setup, it's used specifically on the receiving end. The "Detector" antenna usually has built-in components (like a diode) that convert the high-frequency radio waves it catches into a measurable electrical direct current (DC) signal. This is the crucial tool that allows us to actually map out the shape of the radiation patterns from our other antennas; by moving the detector around the transmitter, we can read the signal strength at different angles and distances.

# Methodology: Experimental Setup and Calibration 🔧🔌

1. Physical Setup of the RF LinkTwo separate antenna mounting masts were positioned on the laboratory bench at a fixed, unobstructed distance from one another. This separation distance was maintained to ensure measurements were taken in the antenna's far-field (Fraunhofer) region, where the electromagnetic wave functions as a fully formed plane wave.

2. Component IntegrationThe Transmitter: A selected antenna module (such as the simple half-wave dipole) was securely mounted to the transmitting mast and connected to the main RF Signal Generator unit using a standard transmission line.The Receiver: A corresponding antenna module was mounted to the receiving mast and connected directly to the field strength meter / RF receiver unit.

3. Alignment and Baseline Calibration (Normalization)Before any structural comparisons or radiation patterns could be measured, the system required a baseline calibration. Both the transmitting and receiving antennas were carefully adjusted so that they were perfectly parallel and facing one another directly (the $0^\circ$ orientation).With the RF generator actively transmitting, the tuning controls and gain adjustments on the receiver were manipulated until the digital or analog readout displayed a precise value of "1".

4. Establishing the Reference PointAchieving this reading of "1" was a critical step in the experiment. It established a normalized maximum reference level ($1.0$ or $100\%$) representing the optimal signal strength transferred when the antennas are perfectly aligned. By setting this baseline, any subsequent changes made to the system—such as swapping to a different antenna module, introducing parasitic elements (like in the Yagi-Uda), or rotating the receiving mast to different angles—could be accurately measured as a relative drop or increase from that established "1" reference point.

# Transmitter and Receiver Setup 📡

# The Transmitter (Tx) Side 📡📶➡️

![transmitter](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/fcb3650313a8448498dbfeeb12551cb0fba274f3/docs/documentation/638247132_921408387047888_1427834736860581240_n.jpg)

- The transmitter side of our setup was responsible for generating the radio frequency signal and launching it into the air. The core of this side was the main RF Signal Generator unit. This device functioned as our oscillator, generating a continuous, high-frequency alternating current (AC). This electrical signal was then guided through a coaxial transmission line up to the fixed transmitting mast, where it connected to the base of our chosen transmitting antenna module (such as the simple half-wave dipole).

- In this configuration, the transmitting antenna acted as a forward transducer. As the high-frequency alternating current flowed into the conductive traces or metal rods of the green PCB module, it created rapidly alternating electric and magnetic fields. These fields detached from the antenna structure and radiated outward into the surrounding free space as electromagnetic waves. For the duration of our specific measurement procedures, the transmitter side was kept entirely stationary to ensure a consistent point of origin for the signal.

# The Receiver (Rx) Side ⬅️📶📡

![receiver](https://github.com/magpantayjohanzrep/LAB-REPORT-4/blob/fcb3650313a8448498dbfeeb12551cb0fba274f3/docs/documentation/637539601_26509557238641995_805112530944791005_n.jpg) 

- Conversely, the receiver side of our setup was designed to capture a portion of those radiating electromagnetic waves and translate them back into measurable quantitative data. This side featured a corresponding antenna module mounted on a separate mast. When the propagating electromagnetic waves from the transmitter washed over the receiving antenna, the process reversed: the fluctuating magnetic and electric fields induced a very small alternating voltage within the receiving antenna's elements.
  
- This induced signal was then fed down into our RF receiver and field strength meter unit, which amplified and quantified the received power. The most important physical feature of the receiver side in our experiment was its rotary base. The receiving mast was mounted on a goniometer (a dial marked with $360^\circ$ of rotation). While the transmitter remained fixed, we manually rotated the receiver side. By observing how the received signal strength—displayed on the meter—fluctuated as the physical angle of the receiving antenna changed, we were able to map out the exact spatial radiation pattern of the module being tested.


# OUTPUT
https://github.com/user-attachments/assets/b86d7d66-e138-40b6-86ad-122feb5c2326

https://github.com/user-attachments/assets/92ded2ba-afe6-4ddd-8c9c-91e132ecff6b

https://github.com/user-attachments/assets/f4034039-7320-4603-add7-7ed31cddd21f


# Reflection/Learning Summary 💡

- Reflecting on this laboratory experiment, the most significant takeaway for me was finally seeing how abstract electromagnetic theories translate into physical, working designs. Before this lab, concepts like "parasitic elements" or "radiation patterns" were just complex diagrams and math equations in a textbook. Getting hands-on experience with the modular green PCB antennas made a huge difference. For instance, physically comparing the simple half-wave dipole to the 5-element Yagi-Uda allowed me to truly conceptualize how adding simple passive metal rods (directors and reflectors) can dramatically focus a signal into a tight, highly directional beam to increase its range.

- Another major "aha" moment occurred during the setup and calibration phase of the experiment. When we aligned the transmitting and receiving antennas to face each other perfectly and tuned the receiver to achieve a baseline reading of 1, it completely shifted my understanding of how RF measurements work. I realized that in practical telecommunications, we are often measuring relative signal strength rather than just absolute power. Establishing that maximum 100% reference point at the 0° direct line-of-sight position was the crucial step that made all our subsequent radiation pattern measurements—the peaks, the side lobes, and the dead zones—actually mean something.

- Ultimately, this experiment bridged the gap between classroom theory and everyday technology. Understanding how a log-periodic antenna achieves its ultra-wide bandwidth by shifting its active region, or how a phased array can steer a beam electronically without moving parts, gives me a completely new perspective on the Wi-Fi routers, 5G cell towers, and TV antennas I see every day. This hands-on practical application has definitely solidified my understanding of foundational antenna topologies and built my confidence for analyzing more complex communication systems moving forward.
