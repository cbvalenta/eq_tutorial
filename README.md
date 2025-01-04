Simple EQ

***This project was created by following a tutorial from @matkatmusic.  The code found here is based on his original repository (found at https://github.com/matkatmusic/SimpleEQ) with
a few creative choices to further learn JUCE coding.***

This project builds an EQ plugin that plays a stereo audio sample and allows the user to change audio settings in real time, including the ability to change:
   - the cutoff frequencies of lowcut, peak, and highcut filters
   - the order of the lowcut and highcut filters (by way of changing the slope)
   - the resonance of the peak filter
   - the gain of the peak filter

This project also visualizes the parameter settings as a response curve to further show the user how the audio settings will affect the audio sample.

This project uses the JUCE code structure for a plugin and is designed to be run as a VST3 plugin.
