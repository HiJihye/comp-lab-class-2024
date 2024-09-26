Description: This folder should contain all the files generated during the setup of your simulation, including files generated after each step of preparation before the actual MD run.
File List:
	•	Initial preparation files (e.g., after energy minimization)
	min.gro
	Equilibration step files (both NVT and NPT)
	nvt.gro: File after NVT equilibration
	npt.gro: File after NPT equilibration
	•	Structure files used in the setup process:
	topol.top: Topology file required by GROMACS
	ions.tpr: File after ion addition
	solv.gro: Solvated structure file