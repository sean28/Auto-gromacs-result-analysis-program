# Auto-gromacs-result-analysis-program
<div style="text-align: justify"> An automatic tool for GROMACS based Molecular Dynamics Simulation Analysis.This tool includes two shell scripts. The first script can automatically process the simulation trajectory, including water removal and periodic boundary removal. The second script can automatically export the xvg files of rmsd, rmsf and radius of rotation, as well as the pdb files of short simulation animation. </div>
<div style="text-align: justify"> <br> </div>
<div style="text-align: justify"> The complete automation script is downloaded <a href="https://drive.google.com/file/d/1r_cButINxK7OOXac5bAF70plWuBRDmiq/view?usp=sharing">here</a>. Please contact the author for use permission and the decompression password .</div>

Usage:
```
sh 0auto_traj_process.sh 
sh 1auto_rmsf_analysis.sh
```
<div style="text-align: justify"> Note: You need to manually select the target during runtime o f this tool. If an error occurs, the script will stop automatically .</div>

<div style="text-align: justify"> <br> </div>
<div style="text-align: justify"> There are another  automatic tool <a href="https://heromdanalysis.wordpress.com">HeroMDAnalysis</a> for GROMACS based Molecular Dynamics Simulation Analysis. HeroMDAnalysis is an automagical tool designed to analyze GROMACS based trajectories from molecular dynamics simulations in .xtc format. It can read required .edr , .xtc and .tpr format particle and energy-based coordinate files for biomolecules then perform analysis of various parameters to finally generate suitable high quality images for visualization and publication. </div>

