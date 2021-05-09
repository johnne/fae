# Feruloyl Esterases repo

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/johnne/fae/binder?filepath=plots.ipynb)

Code used to plot results for article in Frontiers in Microbiology:

*Identification of Novel Putative Bacterial Feruloyl Esterases From 
Anaerobic Ecosystems by Use of Whole-Genome Shotgun Metagenomics 
and Genome Binning*, K. Mogodiniyai Kasmaei & J. Sundh (2019)

[doi:10.3389/fmicb.2019.02673](https://doi.org/10.3389/fmicb.2019.02673)

## How to use

To view an interactive version of the Jupyter notebook `plots.ipynb` click
the binder badge at the top of this Readme. If you instead wish to use the code 
on your local computer follow the steps below.

1. Clone the repo

```bash
git clone https://github.com/johnne/fae.git
```

2. Install and activate the conda environment

```bash
conda env create -f environment.yml
conda activate fae
```

3. Open the jupyter notebook

```bash
jupyter notebook plots.ipynb
```