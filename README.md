# Pitch shifting for specific midi items on render in Reaper

https://forum.cockos.com/showthread.php?t=252702

Minimum repro where 3 individual Midi items are rendering 2 semitones flat.  The rest of the items on the same track render at correct pitch and the rest of the tracks seem to render correctly.

Problem items are within ***Track 5/Midi-G4*** **track between marker 6 and 9** (Midi Items G4-6, G4-7, and G4-8). Rendered time period between **2:05 and 2:53**.

I manually pushed the midi notes up 2 semitones in these project items to compensate so the rendered tracks are at correct pitch.  

Rendered tracks are [in the Tracks folder](./Tracks) for reference.  On my system all of the pitches seem to match except for these 3 sections.  Also, Midi-G5 starting at marker 7 were copy/pasted directly from the problem track and those items render at correct pitch.  Rendered from Tracks 13-16 (routed from Midi, through Instrument tracks with ReaSynth).

*Using ReaSynth as instrument for simple native Reaper repro.  Some of the midi codes are specific to my real instruments and a little hard to listen to, but this demonstrates pitch problem.*

