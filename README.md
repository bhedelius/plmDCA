# plmDCA

This repository is a fork of the original.  It has been modified to write the raw parameters as well as the scores to a mat file.  It also consider gaps in the fasta sequence as an independent 'spin'.

This repository contains MATLAB-code (and accompanying C-written routines) for plmDCA. plmDCA takes as input a Multiple Sequence Alignment and returns scores for pairwise (direct) interactions among the columns. The method is described at length in: 
 
  (1)	M. Ekeberg, C. Lövkvist, Y. Lan, M. Weigt, E. Aurell, Improved contact
 	prediction in proteins: Using pseudolikelihoods to infer Potts models, Phys. Rev. E 87, 012707 (2013)

  (2) M. Ekeberg, T. Hartonen, E. Aurell, Fast pseudolikelihood
	maximization for direct-coupling analysis of protein structure
	from many homologous amino-acid sequences, J. Comput. Phys. 276, 341-356 (2014)
  
If you use plmDCA (modified or as is) for your own research, cite the papers above. See the files for copyright conditions and instructions on how to use the code.

Keywords: plmDCA, pseudolikelihood, direct-coupling analysis, protein structure prediction, contact map, multiple sequence alignment, inverse Ising, Potts model, pairwise Markov random field, learning, inference 
