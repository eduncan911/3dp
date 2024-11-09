# CAD Files

The following STEP files are available:

- ZeroEffs_assembly : The large CAD of all mods to date.
- ministealth_x-carriage : A single body export from the assembly above.
- pandora_extrusionless : A single body export from the assembly above.

This directory holds two types of files.

## .FCStd

This is the source of all CAD.  Take note that these was created in the "LinkStage3" edition of FreeCAD (do not use FreeCAD mainline).

Specifically, the X-Carriage has its feature tree in this file and if you open into FreeCAD mainline, it will break.

## .stpZ

These are compressed STEP files.

If your CAD application does not support compressed step files, you can just unzip the `stpZ` file and then you'll have a normal step file.
