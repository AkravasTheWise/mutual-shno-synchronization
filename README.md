# Spin-wave mediated mutual synchronization and phase tuning in spin Hall nano-oscillators
This reposirtory contains the code used for the micromagnetic simulations in the paper: Spin-wave mediated mutual synchronization and phase tuning in spin Hall nano-oscillators by A. Kumar et al.

The folders contain the files used to simulate the magnetic dynamics of double constriction spin Hall nano-oscillators. Each folder contains:
* The COMSOL files used to produce the current density distribution and Oersted field.
* The Oersted field and current .ovf files necessary to run the mumax3 code.
* The mumax3 code for each biasing current.

Additionally, there are some gifs and images that allow one to study the system in detail. I have not included the full magnetization maps nor the output folders of mumax3, but you can easily generate them by uncommenting line ```//autosave(m, 1 * 1e-11)``` in each .mx3.

# Executive sumary of the paper
This research delves into the fascinating world of **spin Hall nano-oscillators** (SHNOs) and how **propagating spin waves** (PSWs) can be used to control the synchronization between them, opening up new possibilities for spintronics and unconventional computing.

## What Are Spin Hall Nano-Oscillators?

In simple terms, SHNOs are tiny devices that can generate microwave signals by utilizing something called spin-orbit torque. This makes them really attractive for a range of applications, including magnonics (the study and manipulation of spin waves) and **spin wave computing**. Unlike traditional electronic systems that rely on electrons flowing through wires, SHNOs can use spin waves to transfer and process information. Spin waves are collective oscillations of electron spins in a material, and controlling these waves is key for advancing new types of logic circuits and computing systems.
## Key Findings from the Paper

1. **Propagating Spin Waves Drive Synchronization:** In this study, we explored how PSWs can drive the mutual synchronization of two SHNOs. When two SHNOs are placed near each other, they can synchronize their microwave oscillations. But what’s particularly exciting is that the phase of their synchronization can be adjusted and controlled. This means the oscillators can work in in-phase, anti-phase, or even variable-phase synchronization, where the phase difference between them can be tuned from 0 to 180 degrees. This level of control is a big step forward for nano-magnonics and spin-wave logic.

2. **Impact of Distance and Wave Vector:** The distance between SHNOs plays a crucial role in determining how they synchronize. By adjusting the wave vector of the PSWs (which can be thought of as the wavelength of the waves), we were able to study how synchronization changes over different distances between the oscillators. This helps us understand how to design SHNO arrays with more precise control over their behavior.

3. **Controlling Phase Using Current and Magnetic Field:** One of the most interesting parts of the research is that the phase of the synchronized SHNOs can be controlled by adjusting the drive current or applied magnetic field. By doing this, we can fine-tune the oscillators to be perfectly in sync or out of sync, depending on the application. This tunability is crucial for making SHNOs more adaptable for different computational tasks.

4. **Micromagnetic Simulations and Experimental Validation:** To verify these findings, we used micromagnetic simulations alongside phase-resolved Brillouin Light Scattering (µ-BLS) microscopy. These tools allowed us to directly visualize the spin waves and observe how their behavior changes with different current and field settings. The simulations matched the experimental results well, confirming the robustness of our approach.

5. **Applications in Unconventional Computing:** This research has significant implications for unconventional computing platforms like Ising machines and neuromorphic computing, where synchronized oscillations play a key role. The ability to control the phase of SHNO synchronization could help solve complex optimization problems more efficiently and enable new types of spin-wave-based logic systems.

## Conclusion

In this paper, we demonstrated how propagating spin waves can be harnessed to drive variable-phase synchronization between SHNOs. This level of control opens up exciting possibilities for spin wave computing, Ising machines, and beyond. As we continue to explore these systems, I believe SHNOs will become a cornerstone technology for future computing platforms that are faster, more efficient, and more adaptable than today’s electronics.

This work not only pushes the boundaries of what SHNOs can do but also highlights the potential for spintronics to revolutionize computing. If you’re interested in the future of logic circuits and computational devices, keep an eye on the developments in this field—there’s plenty more to come!
