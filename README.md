# elements

A collection of optical component part files used for drawing optical path diagrams in SolidWorks.

## Overview

- **Modeling Software Version**: SolidWorks 2018
- **Directory Purpose**: Common optical components for constructing laser and nonlinear optical experimental optical paths
- **File Types**: `.SLDPRT` and `.SLDASM`

## Parts List

- `ao_lens.SLDPRT`: Concave mirror
- `cylindrical.SLDPRT`: Cylindrical lens
- `etalon.SLDPRT`: Etalon
- `flat.SLDPRT`: Flat element / Planar mirror components
- `hwp.SLDPRT`: Half-wave plate
- `hwpjiazi.SLDPRT`: Half-wave plate holder
- `lens.SLDPRT`: Convex lens
- `pbs.SLDASM`: PBS component assembly
- `pbs1.SLDPRT`: PBS part
- `pinhole.SLDPRT`: Pinhole
- `PowerMeter.SLDPRT`: Power meter
- `SFG.SLDPRT`: Sum-frequency generation crystal
- `SHG.SLDPRT`: Second-harmonic generation crystal
- `yuanjia.SLDPRT`: Mirror mount for holding circular mirror elements

## Recommended Usage

1. Draw the optical path framework (frame.sldprt) as a reference
2. Create a new SolidWorks assembly and insert frame.sldprt. It is recommended that the reference plane of frame.sldprt coincides with the reference plane of the assembly
3. Insert components into the assembly according to optical path requirements and establish geometric relationships between parts and frame
4. Draw appropriate light path elements (sldprt) to represent optical paths and attach them to the framework
5. Render
# sw18-optical-elements
