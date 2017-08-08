# Sf2_Batch_Recording
Script to make samples for SamplerBox from sf2

http://www.samplerbox.org/

Welcome to Sf2_Batch_Recording 
This script let you make some nice wave files from sf2 
it is only a bash script for making some samples for the SamplerBox


TODO
	- are the incoming information from user correct?
	- is the needed software installed?
  	- more options to change file, add reverb and chorus


Welcome Screen :)

Please think before type. I do not catch up mistakes made by user at the momennt.
In later releases i will do. But not yet.
Note, this will take a long time. A simple example:
 
This script needs about 1 second to run. Because of waiting till fluidsynth is started
and sendmidi is connected. This will happen every note.

You want have 127 notes in one velocity and every sample will have 14 seconds
14 sec sample + 1 sec script x 127 samples / 60 sec = 32 Minutes
Test it first with one or two notes
