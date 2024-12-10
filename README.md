# Pixy singularity container

Singularity container with Pixy (https://github.com/ksamuk/pixy) installed through a conda environment.
Originally made as part of NRIS-HPC user support.

This repository can serve as a template to build containers with conda environments from a `environment.yml` file. 

To use the container download it with 
```
$ singularity pull https://github.com/aevenstad/pixy/releases/download/v1.0.0/pixy.sif
```

Test that it is working:
```
$ singularity exec pixy --version

█▀▀█ ░▀░ █░█ █░░█
█░░█ ▀█▀ ▄▀▄ █▄▄█
█▀▀▀ ▀▀▀ ▀░▀ ▄▄▄█
version 1.2.5.beta1
```
