# Hyak-SLURM

Hyak and Mox Hyak are UW's computing cluster.
https://wiki.cac.washington.edu/display/hyakusers/WIKI+for+Hyak+users


### slurmer

SLURM sbatch facilitator. This script is meant to be run as an executable. Slurmer
takes in options via command line to control SLURM variables, creates a temp SLURM 
sbatch file, runs it, and saves logs.

Installation:
On a Hyak build node, run

```
wget https://raw.githubusercontent.com/shervinsahba/Hyak-SLURM/master/slurmer
chmod +x slurmer
```

Now slurmer should be executable from this directory. 
Run `less slurmer` to read through usage instructions.
Make edits to match your preferred defaults.