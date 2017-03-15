# Swift syntax highlighting for Crucible or FishEye

## Installation

All existing syntax highlighting definitions can be found at FISHEYE_HOME/syntax directory.

1. Copy the swift.def file into your FISHEYE_INST/syntax directory. (Note, by copying it in the FISHEYE_INST directory, the swift syntax will persist across upgrades. If you copy it into FISHEYE_HOME, it will need to be reapplied each upgrade).
2. Copy the FISHEYE_HOME/filename.map to your FISHEYE_INST/syntax directory and modify it to map file extensions to definitions.
3. Restart FishEye to pick up the change.
