# Custom_Layout_using_Magic

# CMOS Fabrication (16-Mask Process)

1. Very fist step is to select a substrate which will be having a doping level less as compared to that of wells doping level.

2. Creation of active regions for transistors, SiO2 is deposited on the substrate (which acts as a good insulator) above that Si3N4 silicon nitride is deposited above the SiO2 followed by the  deposition of photoresist. A uv light is passed onto this photoresist which will change the chemical composition of this material depending on the type of photoresist used in the process.

3. Formation of N-well and P-well using the ion implantation in which boron will be used to form the P-well, where as for forming N-well phosphorous is used which will act as a body for the transistors respectively.

4. Formation of Gate

5. Formation of Lightly doped drain (LDD)

6. Source and Drain formation

7. Contacts and localinterconnects are formed by depositing the titanium on wafer surface using sputtering.

8. High level metal formation

# Corner Stiching

It is a way magic uses to represent layers as a non-overlapping tile. Which includes geometries differentiated as solid tile and spcae tile(empty tile). Both of these tiles have a pair of co-ordinates i.e. (right top, top right) & (botton left, left bottom).

Magic store the database in non-ovelapping and overlapping layers
 

```
*watch <layer_name> demo

active well metal
```

Different tile types:

* ntransistor (Diff & Poly)
* ptransistor (Diff & Poly)
* ndiffusion, green, ndiff
* pdiffusion, brown, pdiff
* ndcontacts, ndc
* pdcontact, pdc
* psubstratecontact, psc
* nsubstratecontact, nsc
* polysilicom, red, poly, p
* polycontact, pcontact, pc
* nsubstratendiff, nsd
* psubstratepdiff, psd



