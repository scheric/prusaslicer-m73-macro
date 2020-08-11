# prusaslicer-m73-macro
PrusaSlicer M73 percentage and time conversion to M117 for LCD character display for standard Marlin firmware

# Installation instructions

### 1. Install python and remember the installation directory (This version was tested with python 3)

### 2. Copy script.py and remember storage location     

### 3. Configuration in PrusaSlicer 
Go to: `Print settings` > `Output options` > `Post-processing scripts`

Add: `"[python directory]\python.exe"  "[script directory]\script.py";`

# why does this exist
https://forum.duet3d.com/topic/14675/using-prusaslicers-m73-progress-to-run-macro

Marlin issue

https://github.com/MarlinFirmware/Marlin/issues/18648

Prusa issue

https://github.com/prusa3d/PrusaSlicer/issues/4593

https://github.com/prusa3d/PrusaSlicer/issues/3758

https://github.com/prusa3d/PrusaSlicer/issues/1867

https://github.com/prusa3d/PrusaSlicer/issues/1739

pull Prusa

https://github.com/prusa3d/PrusaSlicer/issues/1317#issuecomment-429428291

pull Marlin

https://github.com/MarlinFirmware/Marlin/pull/15549


extra

https://github.com/MarlinFirmware/Marlin/issues?q=m73
