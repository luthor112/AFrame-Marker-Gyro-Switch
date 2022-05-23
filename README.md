# AFrame-Marker-Gyro-Switch
The code dynamically changes between marker-based AR head-tracking and gyro-based pseudo-AR

**VERY OLD!**
Exported from Glitch.
Uses A-Frame + AFrame-AR (AR.js for A-Frame).
Two markers are needed, because AR.js does not work if you use the same marker preset twice, and because there are no marker-related events emitted that could be used instead of the tick() functions (these could be false by the time you are reading this).