# CoreMPS
![alttext](https://cdn.discordapp.com/attachments/604735153092165642/1113635942301962310/image.png)

The CoreMPS is a complete rebuild of the once-popular Monoprice Maker Select V2 3d printer. The CoreMPS replaces everything except the electronics, heater bed, and hot-end components. The frame was replaced with an aluminum extrusion cube design as opposed to the sheet metal the Monoprice Maker Select V2 came with. 

The CoreMPS also makes use of 3D-printed parts wherever possible in the spirit of RepRap. Reprap is a project started in 2010 that aims to allow printers to self-replicate, meaning that parts are designed and printed on the machine that the part was designed for. All the parts for the CoreMPS were designed with 3d printing in mind, there are no unprintable overhangs and the parts are strong enough to handle loads of high-speed printing. 

The CoreMPS uses CoreXY kinematics, meaning that 2 stationary motors move the gantry in both directions. When the motors rotate in the same direction the gantry will move left and right (X direction) and when the motors rotate in opposite directions then the gantry will move forward and backward (Y direction). If only one motor rotates the gantry will move at a 45-degree angle.

Building the CoreMPS requires pre-existing knowledge of building 3D printers and working with Raspberry Pis. The CoreMPS was designed from scratch over the course of a few weeks and built over the course of a week while parts arrived.

The CoreMPS is capable of printing at 300mm/s and 30k mm/s/s accelerations. Normal non-coreXY printers are usually capable of at most 100mm/s and 5k mm/s/s accelerations. This means that the CoreMPS can print objects up to 100% faster than normal non-coreXY printers.

