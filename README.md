# 2019-LO-SelfAdjusting
This repository contains numerical data for our GECCO 2019 paper: 
[Doerr, Doerr, Lengler: Self-Adjusting Mutation Rates with Provably Optimal Success Rules]
in which we prove performance guarantees for the (1+1) EA with self-adjusting mutation rates on the LeadingOnes function

```bibtex
@inproceedings{DoerrDL19,
  author    = {Benjamin Doerr and Carola Doerr and Johannes Lengler}, 
  title     = {Self-Adjusting Mutation Rates with Provably Optimal Success Rules},
  booktitle = {Proc. of Genetic and Evolutionary Computation Conference (GECCO'19)},
  year      = {2019},
  url       = {https://doi.org/10.1145/3321707.3321733},
  doi       = {10.1145/3321707.3321733},
  publisher = {ACM}, 
  note      = {Full text available at \url{https://arxiv.org/abs/1902.02588}}
}
```

Overview of the files: 
* LO-n10k-Fixed-Target-Results.xlsx has data for the fixed-target plot (Figure 3 in the GECCO paper) for n=10,000. RLS_opt computation can be found on the second tab.
* 10k-Summary-of-MatLabResults-Resampling(1+1)EA.xlsx summarizes a few selected results from our MatLab computations. Plots from Figure 2 can be found here.
* NumericalEvaluation.nb can be used to compute the target mutation rates of the resampling (1+1) EA with self-adjusting mutation rates. Results for different success ratios s can be found in the "data_auto_sXXXX" files, where XXXX/1,000 is the value of the success ratio (e.g., data_auto_s500 has results for s=0.5 and data_auto_s4000 has data for success ratio s=4). We recall that a success ratio of s corresponds to a one-(s+1)-th success rule. 
