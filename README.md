[LICENSE](LICENSE)

# Direct Drive CableCam

This is the version for the ODrive Robotics [motor controller](https://odriverobotics.com/shop/odrive-v35) and the [D5065 dual shaft motor](https://odriverobotics.com/shop/odrive-custom-motor-d5065) with [encoder](https://odriverobotics.com/shop/cui-amt-102).



The CAD program primarily used is Rhino 3D V5.0 ([cablecam.3dm](cablecam_DirectDrive.3dm)) but for better portability the exact same content is exported as AutoCAD ([cablecam.dxf](cablecam_DirectDrive.dxf)) and Step file ([cablecam.stp](cablecam_DirectDrive.stp)).

In case one of the files has a problem, file an Issue in this repository.

Generally speaking, the plans consists of three areas:

## 3D Model of the assembled CableCam using multiple layers
Here the entire CableCam can be seen.
![CableCam_Plan_3D.png](CableCam_Plan_3D.png)

## Drive Shaft assembly
The drive dog is a simple D22x7xd8 disk to be clamped to the motor axle and holds the inline skate wheels.
![Drive_Shaft.png](Drive_Shaft.png)

## Main body in 2D
The main body consists of 2mm thick CFK mostly, except for the base plate where the Gimbal will be mounted on, that is 8mm thick alu and the motor assembly plate made of 4mm alu.
These parts did undergo several iterations of design, e.g. initially some parts were 2.5D elements and had to be milled. To safe costs all has been redesigned to be pure 2D parts and waterjet cutting provide the best result. A clean surface with just a bit of chamfer needed afterwards - to make it perfect - and the cheapest way to manufacture all.
![Waterjet_2D_cutting.png](Waterjet_2D_cutting.png)

## Bill of Material

Item | Qty
-----|-----
Distanzhülse M3x30 Nylon schwarz | 40 
Distanzhülse M6x30 Stahl | 2 
Schraube M6x40 (Laufrad) | 2 
Schraube M6x16 (Laufrad) | 2 
Distanzhülse M3x35 Nylon schwarz | 5 
Schraube M4x50 (Gimbalplatte) | 2 
Stoppmutter M4 (Gimbalplatte) | 2 
Schraube M3x12 | 92 
Schraube M3x40 (Seilkäfig) | 2 
Schraube M3x12 (Encoderbefestigung) | 2 
Stoppmutter M3 (Encoderbefestigung) | 2 
Distanzhülse M3x3 Nylon (Encoder-, Controllerabstandshalter) | 6 
Unterlegscheibe d3x1 Kunststoff (Abstandshalter ODrive Controller) | 6 
Schraube M3x24 (Klemmung Antriebsrad) | 4 
Stiftschraube M4 x 4 mit Ringschneide DIN 916 (Mitnehmer) | 2


## Assembly

[Assembly.md](Assembly.md)
