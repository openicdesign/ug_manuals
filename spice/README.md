# SPICE

SPICE folder has two subfolders: hspice and ngspice. Hspice is widely used in industry and ngspice is open source simulator. 



# HSPICE

## analysis

### noise analysis

```spice
.ac dec 100 10 10G
.noise V(vout) V0 100
```





# NGSPICE



## analysis





### noise analysis

for noise analysis, NOISE command is enough but please make sure to point the output node for output noise check and input voltage or current source as the input noise reference for input-referred noise check. 

```spice
.noise V(vout) V0 dec 100 10 10G
```

