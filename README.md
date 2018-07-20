# singularity-slurm
Singularity recipe for Slurm container 

# On Ceres
```
$ singularity exec --bind /etc/munge --bind /var/log/munge \
--bind /var/run/munge --bind /usr/bin \
--bind /scinet01/gov/usda/ars/scinet/system/slurm:/etc/slurm \
--bind /usr/lib64 --bind /scinet01 
```
