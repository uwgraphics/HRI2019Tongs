
# Design for the Instrumented Tongs
The repository contains Solidworks model files and .STL files for the design of the Instrumented Tongs.

The Instrumented Tongs are used to record large scale object manipulation tasks performed by human demonstrators. The tongs have __Optitrack motion capture markers__ and __ATIMini40 force-torque sensors__.

## 3D printed parts
* The body of tongs along with the 2 pads are 3D printed.
* Directly use the STL files (upper_arm.stl, lower_arm.stl, switchable_plate.stl) to print them. The units are millimeters.
* Nylon or ABS printed with a Fused Deposition Modeling (FDM) printer is recommended however printing with other plastics is possible. Since the tongs are large, printing with a Stereolithography (SLA) printer may produce slightly warped parts during the curing process.  
* The hole pattern where the force torque sensors mount needs to be accurate so printing with a horizontal orientation is recommended.
* The prongs provided for mounting the motion capture markers need to be threaded. Use M4 x 0.7 (tap)die to thread the prongs.

## Small Parts
* Pin - -
* Bushings -
* Spring -
* Screws -

## Advanced Solidworks Users
To modify the tongs start with the assembly file assembly.SLDASM. Open the corresponding parts from the assembly. The file armV2.SLDPRT is the body of the tongs and has two configurations corresponding to the upper and lower sides of the tongs. Use the [configuration manager](http://help.solidworks.com/2018/english/solidworks/sldworks/c_Configurations_Overview.htm) to switch between configurations.
