# MMC-PAC

The folder contains all the files needed to generate the simulation results of the paper *"Determination of Modular Multilevel Converters Admittances and Their Impacts on HVDC Power System Stability"*.
For what concerns the main folder, files have the following extensions:
-	**.pan** : they include the simulations to be carried out with PAN simulator. Each .pan file includes a netlist describing most of the simulated system. Some components are included in form of subcircuits: these are described by the **.mod** and **.va** files.
-	**.mod** : they describe at netlist level some power system components and controls common to each **.pan** file.
-	**.va** : they describe some of the MMC controls implemented with the Verilog-A language.

For further information, please refer to the paper (and its references) or contact the Authors.
