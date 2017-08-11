# Overview
- Sf2_Batch_Recording
Script to make samples for SamplerBox from sf2 for Mac OSX

http://www.samplerbox.org/

- effect_maker
Script to test sox effects and save it for use with Sf2_Batch_Recording
More information below

# Sf2_Batch_Recording 
Welcome to Sf2_Batch_Recording 
This script let you make some wave files from sf2.

This software is needed and has to work from everywhere in the console.

- https://github.com/gbevin/SendMIDI
- https://github.com/FluidSynth/fluidsynth
- https://sox.sourceforge.io/
- screen command

you can install it yourself or via homebrew. I did it via homebrew.

HOW IT WORK

Sendmidi will send a note to Fluidsynth. Fluidsynth will play the sound and record it to a 
raw file. Sox will convert the raw file to a signed 16bit 2 Channel wav file.



Welcome Screen :)

Note, this will take a long time and it will not really work when your mac goes to sleep.
I will use caffeinate -dim for it. It will be automatically killed on end of the script 
but if break the script with ctrl-c you have to kill caffeinate yourself.


A simple example:
 
This script needs about 1 second to run. Because of waiting till fluidsynth is started
and sendmidi is connected. This will happen every note.

You want have 127 notes in one velocity and every sample will have 14 seconds

14 sec sample + 1 sec script x 127 samples / 60 sec = 32 Minutes

Test it first, with one or two notes.

You will be asked at start and before conversation for:

Velocity,
First Note,
Last Note,
Sample length, 
Gain,
Debugmode to hear the sound past conversation,
Effects

I tested it with note 60. But you can choose whatever you want.

# effect_maker

You can try and play with effects from Sox.
If you are happy with that effect you can save it and use it with Sf2_Batch_Recording and generate your wav samples including effects.
