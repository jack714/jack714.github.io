## Radiation Health Engineering Lab Glow Curve Analysis Research      Fall 2020 - Winter 2021

**Project description:** 

I participated as an Undergraduate Research Opportunity Program researcher in the RHE lab. Under Professor Kim Kearfott's guidance, I worked closely with lab member Jack Thiesen to develop a new glow curve analysis software.

Thermoluminescent dosimeters integrate incoming ionizing radiation dose and release photons proportional to it. When heat is applied to the material, peaks in the emitted light occur at different temperatures corresponding to characteristic quantum states. Separating these peaks may be done through fitting the data to thermoluminescence models, in a process called glow curve analysis. This analysis reveals information about signal fading and has the potential to improve dose quantitation.

In the research, I coded a software using C++ that automatically subtracts the background noises from raw data, removes any discontinuous spikes, and identifies the peaks. A light version of the Savitzky-Golay algorithm is implemented to smooth data. I designed a low-pass filter to remove spikes and used gradient descent to further process the identified peaks. The final software fits the approximate curve for each peak according to first-order kinetic physics and outputs a figure of merit for the fit. The final executable compatible with different computer systems allows greater portability.

I participated in the Engineering Research Symposium hosted by University of Michigan and presented a poster on the spike-removal algorithm.

The glow curve analysis team was invited to the exclusive MTV workshop and presented a poster on our software.

My team's written paper "Preliminary Thermoluminescent Dosimeter Glow Curve Analysis with Automated Glow Peak Identification for LiF:Mg,Ti" is scheduled for publication in Spring 2021.

### 1. TLD 100 glow curve analysis visualization

<img src="images/TLD-100.jpg?raw=true"/>

### 2. Engineering research symposium poster

<img src="images/poster.jpg?raw=true"/>

### 3. Paper publication 
<img src="images/paper.jpg?raw=true"/>
