README.md
=========

This script is designed for Open Broadcaster Software (OBS) and provides two text sources with counters that can be incremented, decremented, reset to the starting value, or set to a custom value through hotkeys.

Requirements
------------

This script requires the OBS Python module, `obspython`, which can be installed through OBS itself.

Usage
-----

To use this script, add a new Text (GDI+) source for each counter you want to create. Name each source and set its text to the desired starting value.

In the script's properties, select the sources you just created for each of the two counters. You can also customize the starting value for each counter, and the text that appears before the number in the counter.

Once the script is configured, you can use the following hotkeys to interact with the counters:

Counter 1

-   Increment: `[Ctrl] + [Up Arrow]`
-   Decrement: `[Ctrl] + [Down Arrow]`
-   Reset to starting value: `[Ctrl] + [Shift] + [R]`
-   Set to custom value: `[Ctrl] + [Shift] + [C]`

Counter 2

-   Increment: `[Alt] + [Up Arrow]`
-   Decrement: `[Alt] + [Down Arrow]`
-   Reset to starting value: `[Alt] + [Shift] + [R]`
-   Set to custom value: `[Alt] + [Shift] + [C]`

You can customize the hotkeys by opening the OBS hotkey settings and editing the ones associated with this script.
