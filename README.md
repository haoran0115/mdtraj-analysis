# Tutorial on Molecular Dynamics Trajectory Analysis

## Introduction
This is an example of MD trajectory analysis.

## Main content
* For the tutorial, please refer to `./notebooks/main.ipynb`. You should use Jupyter Notebook or Jupyter Lab to open this notebook.
* The 6j83 system under `./6j83`
    - Amber topology file `./6j83/6j83_solv.prmtop` (which records information like structure connectivity, force constant, and etc.)
    - Amber coordinate file `./6j83/6j83_solv.inpcrd` (not useful in this tutorial, just for reference)
    - PDB file `./6j83/6j83_solve.pdb`
    - Original trajectory `./6j83/6j83_mdtraj.nc`
* AmberTools script for cpptraj `./6j83/*.in`

```
.
├── 6j83
│   ├── 6j83_dry_499.pdb
│   ├── 6j83_mdtraj_aligned.nc
│   ├── 6j83_mdtraj.nc
│   ├── 6j83_solv.inpcrd
│   ├── 6j83_solv.pdb
│   ├── 6j83_solv.prmtop
│   └── align.in
├── images
│   ├── 6j83_mdtraj_aligned.gif
│   └── 6j83_mdtraj.gif
├── main.ipynb
└── README.md
```

## Useful links and manuals for tools
* cpptraj: [https://amber-md.github.io/cpptraj/CPPTRAJ.xhtml](https://amber-md.github.io/cpptraj/CPPTRAJ.xhtml)
* Jupyter lab: [https://docs.jupyter.org/en/latest/install.html](https://docs.jupyter.org/en/latest/install.html)
* mdtraj: [https://www.mdtraj.org/](https://www.mdtraj.org/)
* Matplotlib: [https://matplotlib.org/](https://matplotlib.org/)

