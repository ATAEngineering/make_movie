# make_movie Utility
This utility was developed by [ATA Engineering](http://www.ata-e.com) to mimic
the functionality of Loci/CHEM's **extract_movie** capability, but add support
for boundary, cut plane, and isosurface output data. It can be used to write
out surface data from a Loci/CHEM simualation in Ensight format, such that
it can be viewed as an animation in ParaView.

# Dependencies
This python utility requires the multiprocessing and argparse libraries.

# Usage
Detailed usage can be found by passing the script the **-h** or **--help** 
options. An example of usage is shown below.

```
make_movie -h
```
```
make_movie -c myCase -s 10 -e 100 -i 10 -t 1e-5 -b BC_1,BC_2 -v qdot,pg
```

