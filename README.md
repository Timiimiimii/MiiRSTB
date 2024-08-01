# MiiRSTB
 A simple CMD tool for editing RSTB files for Nintendo Switch Sports.

## usage
Converting to yaml `MiiRSTB.exe [.yaml file]`  
Converting to RSTB `MiiRSTB.exe [.rsizetable.zs file]`  
Merging `MiiRSTB.exe [--merge/-m] {Vanilla RSTB} {Modded RSTB} {Output RSTB Name}`  
Patching `MiiRSTB.exe [--patch/-p] {Vanilla RSTB} {RSTB Yaml patch} {Output RSTB Name}`  
Make Patch `MiiRSTB.exe [--makepatch/-mp] {Vanilla RSTB} {Modded RSTB}`

Note: MiiRSTB will always choose the entry with the highest value, removing entries will result in the program choosing the vanilla.

### Building
Requires my fork of [RstbLibrary](https://github.com/Timiimiimii/RstbLibrary)
