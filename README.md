
# FULL

FULL is a prototype of a **conveyor belt 4 axis tangential rotary knife cnc fabric cutter** for single ply cutting.

![Fabric Cutter](https://github.com/rbuttress/dinner/blob/main/dinner.jpeg)
[https://www.youtube.com/watch?v=8nrIL4Qvl0I](https://www.youtube.com/watch?v=8nrIL4Qvl0I&ab_channel=RoseButtress)
## Hardware

.STEP files provided for modification and customization

.STL files for 3D printed components

[Conveyor Belt Design Considerations](https://accurateindustrial.com/resources/articles/3-basic-conveyor-belt-tracking-rules-to-follow/)

Controller: [synthetos/TinyG](https://github.com/synthetos/TinyG/wiki)

Drivers: [CL86T-V41](https://www.omc-stepperonline.com/index.php?route=product/product/get_file&file=3155/CL86T-V41.pdf), [DM542T](https://www.omc-stepperonline.com/index.php?route=product/product/get_file&file=382/DM542T.pdf), [CL42T](https://www.omc-stepperonline.com/index.php?route=product/product/get_file&file=884/CL42T.pdf)

## Gcode

After Generating XYZ gcode, you can use this crude node.js app to convert it to XYZA gcode to maintain the tangential angle of the cutting blade to the line being cut. It doesn't work with arcs so you'll have to convert arcs to line segments first. TinyG can barely handle arcs anyway so you'll need to develop a workflow around that anyway

[https://github.com/rbuttress/xyz2xyza](https://github.com/rbuttress/xyz2xyza)

## Acknowledgments

This work was created with support in part from The Center for Craft, MSAC, and The Processing Foundation.

Special Thanks to Lo, Alan Grover, Kristin Prim, Quentin Gibeau, Monica Mirable, Yanni & Eva, Haniel Wides, Jesus, Colin Foster, Didi, and Jake Read

