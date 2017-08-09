# Sf2_Batch_Recording
Script to make samples for SamplerBox from sf2 for Mac OSX

http://www.samplerbox.org/

Welcome to Sf2_Batch_Recording 
This script let you make some nice wave files from sf2 
it is only a bash script for making some samples for the SamplerBox

This is needed and have to work from everywhere in the console.

- https://github.com/gbevin/SendMIDI
- https://github.com/FluidSynth/fluidsynth
- https://sox.sourceforge.io/
- screen command from the console. maybe you need the command line tools from xcode or you install it via homebrew

you can install it yourself or via homebrew. I did it via homebrew.

TODO
- are the incoming information from user correct?
- is the needed software installed?
- more options to change file, add reverb and chorus via sox
- quick test play for the sox options



Welcome Screen :)

Note, this will take a long time. A simple example:
 
This script needs about 1 second to run. Because of waiting till fluidsynth is started
and sendmidi is connected. This will happen every note.

You want have 127 notes in one velocity and every sample will have 14 seconds

14 sec sample + 1 sec script x 127 samples / 60 sec = 32 Minutes

Test it first with one or two notes
