## Documentation for Generic AD828 Amplifier Boards

These audio amplifier opamp boards are commonly available on sites like Amazon, Alibaba and eBay, but there does not seem to be any schematics for them.

They appear to use a classic AC coupled inverting amplifier design and provide some through holes for adding feedback resistors.

The circuit is relatively simple, but without documentation requires requires some reverse engineering to calculate what the feedback resistors should be for a given gain.

Here is an accurate recreation in KiCAD, including spice simulations and gain resistor settings.

Note that the listed resistors are added in parallel to the existing 20k SMD resistor (the listed resistance is not the actual feedback resistance)

![3D Render of the board](3D_View.png)

<img width="770" height="533" alt="SchematicOverview" src="https://github.com/user-attachments/assets/ba246a4e-8b54-4d29-aa12-a0781aec9b9a" />

