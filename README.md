# PitchPerfect
The Pitch Perfect app allows users to record a sound using the device’s microphone.<br /> 
It then allows users to play the recorded sound back with six different sound modulations: Chipmunk, Darth Vader, Super Slow, Super Fast, Reverb and Echo.
## Implementation
The app has two view controller scenes:<br />
- RecordSoundsViewController - Allows users to record a sound.  
- PlaySoundsViewController - Allows users to play the recorded sound back with effects.

#### RecordSoundsViewController

The record sounds view is the initial view for the app, and consists of a button with a microphone image.
Tapping this microphone button will start an audio recording session and present a stop recording button. 
The app will use code from AVFoundation to record sounds from the microphone.
When the stop button is clicked, the app should complete its recording and then push the PlaySoundsViewController onto the navigation stack.

#### PlaySoundsViewController

The play sounds view has six buttons to play the recorded sound file and a button to stop the playback.
The buttons for playing the recorded sounds will have images corresponding to their sound effect:<br />
- Chipmunk image → High-pitched sound<br/>
- Darth Vader image →  Low-pitched sound<br/>
- Snail image → Slow sound<br/>
- Rabbit image → Fast sound<br/>
- Bird image → Echo sound<br/>
- Reverb image → Reverb sound<br/>
