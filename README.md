# Aeolian-Spider-Web

Subtractive

Wave: Determines the waveform of the oscillator between a sine, triangle, saw, and square. 

Octave: Offsets the pitch of the oscillator from the incoming note in octave intervals.

Semi: Offsets the pitch of the oscillator from the incoming note in semitone intervals.

Fine: Offsets the pitch of the oscillator from the incoming MIDI note in cent intervals.

Mix: Crossfades the volume of subtractive oscillators A and B.

Gain: Sets the gain of the subtractive section.


Additive

Harmonic Gains: Sets the gain for each additive harmonic. See also Aeolian Mode below.

Harmonic Pans: Sets the panning for each additive harmonic.

Harmonic Multipliers: Sets the frequency multiplier for each additive harmonic.

Octave: Offsets the pitch of the oscillator from the incoming note in octave intervals.

Semi: Offsets the pitch of the oscillator from the incoming note in semitone intervals.

Fine: Offsets the pitch of the oscillator from the incoming MIDI note in cent intervals.

Reset: Resets all the harmonic gains, pans and multipliers.

Random: Randomizes the harmonic gains. Also randomizes the multipliers if the mult toggle is checked.

Mult: If checked, randomizing the harmonics also randomizes the multipliers.

Mix: Sets the gain of the mixed additive section.

FM Mod: Sets the depth of frequency modulation applied to the additive section by the dedicated sine fm modulator.

FM Freq: Sets the frequency of the dedicated sine fm modulator.


Amplitude Envelope

A: Determines the length of the attack portion of the envelope.

D: Determines the length of the decay portion of the envelope.

S: Determines the sustaining volume of the envelope.

R: Determines the length of the release portion of the envelope.


Pitch Envelope

A: Determines the length of the attack portion of the envelope.

D: Determines the length of the decay portion of the envelope.

S: Determines the sustaining volume of the envelope.

R: Determines the length of the release portion of the envelope.

Mod: Determines the depth of modulation applied to the oscillator pitch by the envelope.


Pitch LFO

Wave: Determines the waveform of the LFO between a sine, triangle, saw, and square. 

Mod: Determines the depth of modulation applied to the oscillator pitch by the LFO.

Rate: The speed of the modulation. When in sync mode the control and rate is determined by a division of the incoming BPM. When in free mode the control and rate is determined by frequency in hertz.

Sync: Switches the LFO rate between hz and BPM sync modes.

Retrig: When off the LFO will continuously run through the wave cycle. When On the LFO cycle retrigger with each new played noyte.


Filter

Type: Choice between lowpass and highpass filter types.

Cut: Determines the cutoff point of the filter.

Res: Sets the resonance of the filter.


Filter Envelope

A: Determines the length of the attack portion of the envelope.

D: Determines the length of the decay portion of the envelope.

S: Determines the sustaining volume of the envelope.

R: Determines the length of the release portion of the envelope.

Mod: Determines the depth of modulation applied to the filter by the envelope.


Filter LFO

Wave: Determines the waveform of the LFO between a sine, triangle, saw, and square. 

Mod: Determines the depth of modulation applied to the filter by the LFO.

Rate: The speed of the modulation. When in sync mode the control and rate is determined by a division of the incoming BPM. When in free mode the control and rate is determined by frequency in hertz.

Sync: Switches the LFO rate between hz and BPM sync modes.

Retrig: When off the LFO will continuously run through the wave cycle. When On the LFO cycle retrigger with each new played noyte.


Chorus

Delay: Set the delay offset between the original and effected signal.

Rate: Set the rate of modulation of the chorus circuit.

Depth: Set the depth of modulation of the chorus circuit.

Wet: Set the mix between the original and effected signal.


Delay

Time: Set the delay time in tempo divisions.

Fb: Set the gain of the delay feedback.

Wet: Set the mix between the original and effected signal.


Presets

Save: Saves the preset to the browser download folder with the name give in the save name field.

Save Name: Sets the name for a preset to be saved. Must include the .txt file extension. 

Load: Loads the preset from the location indicated in the load path field.

Load Path: Sets the online path from which to load a preset from. Must include the .txt file extension.


MIDI

Driver Select: If the browser supports MIDI, allows selection of a MIDI device.

Monitor: Displayed incoming MIDI activity.

Learn: When a valid MIDI driver is selected and MIDI learn is enabled, moving any parameter on the interface and then moving the source MIDI controller will create a link between the controller and the parameter. When MIDI learn is disabled, moving the MIDI controller will move the parameter on the interface.

Velocity: Determines whether the amplitude envelope will respond to incoming MIDI velocity information or not.

Pitch Bend: Pitch bender visuallising the MIDI pitch bend controller. Allows "bending" of the played notes based on the pitch bend range setting.


Main Settings

Start Audio: Starts the browser audio engine for the synth.

Gain: Determines the overall volume output of the synthesizer.

BPM: Deterimnes the base tempo for the LFO and delay divisors.

Bend Range: Sets the pitch bend range of incoming MIDI pitch bend information by semitone intervals.

Drone: When turned off the amplitude envelope starts the release stage when a note is no longer playing. When turned on the amplitude envelope does not trigger the release, allowing for a continuous droning tone.

Aeolian: When turned on slow randomized LFOs modulate the amplitudes of each harmonic on the additive section. Every time the toggle is switch on, these LFOs are randomized with new parameters. When turned off no modulation is applied to the additive harmonic gains.

# Demo here: https://faxinadu.net/jstest/tone/synth/
