# Swift syntax highlighting for Crucible or FishEye

## Installation

Note: All existing syntax highlighting definitions can be found at `FISHEYE_HOME/syntax` directory.

1. Copy the `swift.def` file into your `FISHEYE_INST/syntax` directory. (Note, by copying it in the `FISHEYE_INST/syntax` directory, the swift syntax will persist across upgrades. If you copy it into `FISHEYE_HOME/syntax`, it will need to be re-applied each upgrade).
1. Add the lines from `filename.map` to your `FISHEYE_INST/syntax/filename.map`. If the file `FISHEYE_INST/syntax/filename.map` does not exist, you can just copy the file `filename.map` to the `FISHEYE_INST/syntax` directory.
1. Restart FishEye to pick up the change.
