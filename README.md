# Heavy Examples for Daisy

These are template and example patches for the Electro-Smith Daisy platform.

Included in this directory are JSON files, and accompanying template
patches for the various Daisy dev kits.

The patches are set up to use all of the components included in the
JSON, and print changes to the inputs via Serial.

These are expected to be compiled for the corresponding target board
with Debug printing enabled, and patch size set to "Big".

In addition to printing changes to the inputs (buttons, pots, CVs,
etc.), CV outputs will generate waveforms on the devkits that have them,
and LEDs will either respond to inputs (desktop), or blink a repeating
pattern (eurorack, pedal).

In each template, audio and MIDI are configured to do pass through
(`[adc] -> [dac]`, `[notein] -> [noteout]` respectively).
MIDI note input is also printed over serial.

## Devices

* Pod
* Petal
* Patch
* Field
* Patch.Init()
* Pedal Devkit
* Desktop Devkit
* Eurorack Devkit
