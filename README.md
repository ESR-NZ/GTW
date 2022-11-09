# GTW
Genomics training week notes and install instructions

## Dependencies
### WSL
This repo assumes a windows laptop with Ubuntu 20.04 LTS up an running under Windows Subsystem fro Linux [WSL](https://learn.microsoft.com/en-us/windows/wsl/install).

----

## System tools
```bash
sudo apt-get install --yes gcc g++
sudo apt-get install --yes make
```

----

## Flye
Flye github as key guide [here](https://github.com/fenderglass/Flye/blob/flye/docs/INSTALL.md)

### INSTALL
```bash
wget https://github.com/fenderglass/Flye/archive/refs/tags/2.9.1.tar.gz
tar -zxvf 2.9.1.tar.gz
```

----

## Kraken2
Details [here](https://github.com/DerrickWood/kraken2/)

### INSTALL
```bash
wget https://github.com/DerrickWood/kraken2/archive/refs/tags/v2.1.2.tar.gz
tar -zxvf v2.1.2.tar.gz
cd kraken2-2.1.2/
bash install_kraken2.sh ~/kraken2
```


```bash
cd ~/
sudo cp ~/kraken2/kraken2{,-build,-inspect} /usr/bin/
```

```bash
cd ~/krakenDB
wget -c https://refdb.s3.climb.ac.uk/kraken2-microbial/hash.k2d
wget https://refdb.s3.climb.ac.uk/kraken2-microbial/opts.k2d
wget https://refdb.s3.climb.ac.uk/kraken2-microbial/taxo.k2d
```

### TEST DATA
```bash
wget https://github.com/fenderglass/Flye/blob/flye/flye/tests/data/ecoli_500kb_reads.fastq.gz
```



