# Pitch shifting for specific midi items on render in Reaper

https://forum.cockos.com/showthread.php?t=252702

Minimum repro where 3 individual Midi items are rendering 2 semitones flat.  Using ReaSynth as instrument for simple native Reaper repro.  Some of the midi codes are specific to my real instruments but this demonstrates pitch problem.

Problem items are in the *Midi-G4* track between marker 6 and 9 (Items G4-6, G4-7, and G4-8).

I manually pushed the midi notes up 2 semitones to compensate so the render tracks are at correct pitch.  

Rendered tracks are [here](./Tracks) for reference.  On my system all of the pitches seem to match except for these 3 sections.  Also, Midi-G5 starting at marker 7 were copy/pasted directly from the problem track and those items render at correct pitch.