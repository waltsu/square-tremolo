# Square Tremolo

A JSFX tremolo effect plugin for REAPER that uses a square wave modulator instead of the traditional sine wave.

## Description

Unlike conventional tremolo effects that use a smooth sine wave to modulate volume, Square Tremolo uses a square wave to create distinctive "on-off" characteristics in your signal.

The effect alternates between full volume and a reduced volume level at a specified frequency, creating a pulsing or stuttering sound.

## Features

- **Frequency (Hz)**: Control the rate of the tremolo effect (0-100 Hz)
- **Off-Level (dB)**: Set the volume during the "off" portion of the cycle (-60 to 0 dB)
- **Duty Cycle (Pulse Width)**: Adjust the ratio between "on" and "off" time (0.0 to 1.0)
  - 0.5 = equal on/off time (50% duty cycle)
  - Higher values = longer "on" time
  - Lower values = longer "off" time

## Installation

1. In REAPER, go to **Options → Show REAPER resource path in explorer/finder...**
2. Navigate to the **Effects** folder within the resource path
3. Copy the `square-tremolo` file into the Effects folder
4. Restart REAPER or refresh the plugin list:
   - Open the **Add FX** screen on any track
   - Select the **JS** section
   - Click **Scan for new plugins**
5. The plugin will appear as "Square Tremolo" in the JS effects list

## Author

Valtteri Virtanen

## Credits

Modified version of REAPER's stock tremolo plugin.
