# Simulating quantum many-body dynamics on a current digital quantum computer (Cirq - Google Quantum AI)

**FOPRA 34, July 2022**

The field of quantum many-body physics covers a wide range of systems with increasing scale, with many relying on numerical simulations to solve their equations. Quantum computing devices are an ideal platform to explore these open questions, as they are able to naturally handle the exponential complexity of a quantum system. This report studies dynamical phase transitions, a quantum many-body phenomena, in a specific Ising model using simulations with the [Google Cirq framework](https://quantumai.google) for noisy intermediate scale quantum computing. The code uses common methods in quantum simulation, such as Trotterization, Generalized Amplitude Damping channel and Tomography, to run a local simulation that mirrors the protocol used to control and compute on a real quantum device. The theoretical groundwork and coding tasks are taken from the manual provided [1]. The report summarizes some of the core theoretical concepts needed for the exercises and discusses the results of the simulations.

<p align="center">
<img src="plots/cover.jpg" alt="drawing" width="75%"/>
</p>

Full report: [here](/report.pdf)

----
## Authors:
* @Franzvst: Franz Von Silva Tarouca
* @gnandt: Christian Gnandt
* @EmilianoG-byte: Cristian Emiliano Godinez Ramirez

---
[1] Practical Training, Condensed Matter Theory, Technical University Munich
Physics Department.  Prof. Dr. Michael Knap.  [Sources.](/sources/)
