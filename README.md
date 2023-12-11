**For the simulation run the following steps:**

```
git clone https://github.com/BAMresearch/MultilayerInternalStresses.git

cd MultilayerInternalStresses

unzip without-reaction-layers.zip

unzip with-reaction-layers.zip

abaqus j=without-reaction-layers cpus=[Number of CPUs]

abaqus j=with-reaction-layers cpus=[Number of CPUs]
```
