
Quantum Mechanical Modeling of Light Harvesting Apparatus of genus _Rhodopseudomonas_ : Thorough Structural Analysis, Hamiltonian modeling based on structural symmetry,Integrating Correlated $C_{2}$ Site Energy Modulation and Gaussian Diagonal Disorder for Absorption Spectrum Simulations Under High Light and Low Light Conditions.
			
- This was a **side-project/detour** from the main project. It taught me to model and develop codes for diabatic Hamiltonians, and spatial configurations of transition dipole moments for non-trivial aggregates. The LH2 light harvesting complex present in members of the genus Rhodopseudomonas had the perfect amount of complexity to act as a good exercise for me to develop these skills.
			
- **Basics** : Read about Frenkel Excitons, the architecture and function of the light-harvesting apparatus of purple bacteria , from [Cogdell et al.’s](https://www.cambridge.org/core/journals/quarterly-reviews-of-biophysics/article/abs/architecture-and-function-of-the-lightharvesting-apparatus-of-purple-bacteria-from-single-molecules-to-in-vivo-membranes/D00B5DE013531C889C4B2B9334FD7C93)$ review on the topic.
			
- **Advanced**: Went through  [Kohler et al.‘s](https://doi.org/10.1098/rsif.2017.0680)$ experimental observations to gain a deeper understanding of the structure and the spatial configuration of transition dipole moments of the complex. Thoroughly read [Brotosudarmo et al.’s](https://doi.org/10.1016/j.bpj.2009.06.034) paper and it's SI, which contained all the necessary technical details about various parameters for the simulations ( obtained from experimental observations by the same group). 
			
- **Result**: Two scalable diabatic Hamiltonians were  modeled, for simulations under  LL and  HL conditions respectively. Upon inclusion of correlated C2 type diagonal disorder, the experimental observations could be reciprocated ( peaks at 800, 820 and 850 nm for LL complexes, and 800, 850 nm for HL complexes). **All codes were written in Julia**			 
			
	
	
