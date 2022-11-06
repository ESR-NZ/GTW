# GTW
Genomics training week notes and install instructions

## Dependencies
### WSL
This repo assumes a windows laptop with Ubuntu 20.04 LTS up an running under Windows Subsystem fro Linux [WSL](https://learn.microsoft.com/en-us/windows/wsl/install).


----

## Conda
- Basics taken from [here](https://gist.github.com/kauffmanes/5e74916617f9993bc3479f401dfec7da)
- Anaconda3-2022.10-Linux-x86_64.sh	737.6M	2022-10-17 16:15:39	e7ecbccbc197ebd7e1f211c59df2e37bc6959d081f2235d387e08c9026666acd


### INSTALL
```bash
wget https://repo.anaconda.com/archive/Anaconda3-2022.10-Linux-x86_64.sh
bash Anaconda3-2022.10-Linux-x86_64.sh
```

----
## RESTART WSL
----

## Flye
Flye github as key guide [here](https://github.com/fenderglass/Flye/blob/flye/docs/INSTALL.md)

### INSTALL
conda install -c bioconda flye

----

## Kraken2
git clone https://github.com/DerrickWood/kraken2/
cd kraken2
bash install_kraken2.sh


