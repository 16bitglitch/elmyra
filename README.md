# Elmyra

Elmyra is a DIY drone synthesizer, inspired by the Soma Lyra-8. It runs on the Adafruit ItsyBitsy M0 Express microcontroller and has added analog distortion and filter. For build documentation and more info, see here: https://neutral-labs.com/elmyra

Elmyra AE Alt Firmware 0.1 by Charles Gershom

 I really like the look feel and nearly all of the sound elements of elmyra. Neutral Labs did a great job. 
 The only thing that really bugged me is that the oscillators had a baked in noise element which turned out 
 to be a random number applied to each sample. Now I love noise, but I also like an element of control. The filter 
 on this thing is absolutly filthy and I love it. So what i really wanted is some cleaner oscillators that I can 
 dirty up in a controlled way. Hence the changes below. Playing single clicks and clean purer tones into the delay and 
 that dirty dirty lovely scratch filter is so much fun. 

 I havent tried these tweaks with sequencer mode as i dont really use it. Some stuff may break, or be weird. 

 Here is a list of changes:
 
*Pitch for each oscillator now cos from ultra low frequency clicks to approx 2x the stock max pitch

*Random oscillator noise was removed by default, and now lives on the Mod Knob. Increase noise along side the usual mod function

*Mod Max values are bigger

*Slew for changes in things such as notes have been dramatically reduced

This is based on the latest stock firmware. 

