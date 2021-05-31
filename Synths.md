# Synths

## Terminology

**subtractive** - Start with a harmonically rich signal and remove frequencies using filters.
**additive** -
**frequency modulation (FM)** - The frequency of a waveform is changed by modulating its frequency with a modulator. The frequency of an oscillator is altered "in accordance with the amplitude of a modulating signal". Start with simple, pure signals like sines and use FM to modify sounds.

Can be controlled with an lfo. At low frequency, the lfo imparts vibrato-like effects. Once lfo reaches audio frequencies, FM starts to control tambre.
**operator** - Chain of an oscillator/amplifier with amplitude controlled by an envelope
**oscillator** - Signal generator providing audio signal. Frequency is in audible spectrum.
**filter** - Integrated signal filtering. Can choose from filter types
**amplifier** - Controls volume. Often has panning.
**lfo** - Low frequency oscillator used to time/control synth parameters. Often below frequency spectrum.
**noise** -

## Ableton Analog

https://www.ableton.com/en/manual/live-instrument-reference/

https://www.youtube.com/watch?v=3H0UhHnR95Y

### Concepts / controls

* Each small section has a separate set of controls in the middle
* 2 oscillators, filters, amps, lfos
* Can choose signal routing between the pairs
* Each chain has separate volume and filter fader
* Has a pitch ramp. Quick ramp useful for percussion.
* Has oscillator control section
    * Pitch mod - Change for pitch either from LFO or keyboard
    * Pulse width - Width for square wave oscillator
    * Sub/sync - sub=sub-octave oscillator, sync=some other thing?
* 2 filters are ADSR filter envelopes
* Filters have loop control which will loop various parts of the envelope
    * Analog is polyphonic, so using loop control with create unique rhythm for each voice.
    * Freq mod - Frequency modulation. Either controlled by lfo or correlated with register on keyboard (higher register=more open filter)
    * Resonance mod - Resonance modulation. Frequency width of filter resonance. Useful for formant filters in changing vowels.
    * Filter 1 has a fader to route to filter 2
* Amplifiers have panning and volume filter controls

## Ableton Operator

https://www.youtube.com/watch?v=ngojWlvfahI

* FM synthesizer
    * Usually you want to use a simple oscillator for FM to make things easier to control
* Has 4 operators which can each be independently controlled
* Each operator has 2 control sections
    * Envelope - Envelope for amplitude
    * Oscillator - Controls oscillator. Allows visualizing frequency bands and custom drawing too
        * Using Shift+drag only draws on that harmonic multiple
        * Right-click allows choosing odd or even harmonics
    * Repeat - How much harmonics repeat
    * Feedback - How much oscillator modulates itself (wtf?)
* When you have a modulator oscillator, changing it's properties changes the tambre of the modulated oscillator. It doesn't change the pitch. (Mental model?)
* Right-click allows cloning envelopes
* lfo can be directed to any of the operators. Can also set destination to other properties.

## Neurobass w/ Ableton Operator + underbelly

https://www.youtube.com/watch?v=5RNBLgC455s

"OTT is the MSG for EDM"

* Use operator in parallel algorithm
* Glide at 150 ms
* Typically neuro uses square wave. Emulate with oscillator a as sin and add in 5th harmonic in oscillator b and 7th in c.
* Turn up fine on osc a 15c for some flava.
* Look at filter and notice where we get action on freq sweep
* Ctrl+G to group into instrument rack, right click on freq and map to macro 1, open map mode, set viable range.
* Increase resonance to 50%
* Add saturator: drive +25db, output -25db, soft clipping
* Add OTT at 70%
* EQ to increase myspace frequencies (120hz), cut frequencies above
* Add a bandpass auto filter with lower slope
    * Find range where filter is maxing out. Map to macro same and limit range again.
    * Cuts out too much crisp. Ctrl+G to put in rack. Open chain and rename chain to BP
    * Create chain (two chainz!) thru and bring up to hear crisp
* Another OTT
* EQ after auto filter: reduce myspace
* Note: Sounds a bit anemic
* Every neurobass will be a bit different. Hang on to all of them, them mix and match.
