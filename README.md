# NearField-BinauralDecoder
In this repo you can find mcfx-convolver presets for Ambisonic Binaural Decoders that are able to render near-field sources. The decoders are based on BRIRs (Binaural Room Impulse Responses) and are loaded as filters to the mcfx convolver plug-in by Matthias Kronlachner.

Workflow: 
1) Create encoder track in Reaper and load a IEM StereoEncoder plug-in. 
2) Load a mcfx-convolver64 (for 7th order) plug-in on the decoder track and select the .config of the filters from your local path.
3) Drag the source icon to the negative hemisphere for near-field effects (grey source icon).
