Sound-Reactive-LED-MEMs-Microphone-Prop
========================================

Modified example code from the [Interactive LED Music Visualizer](https://learn.sparkfun.com/tutorials/interactive-led-music-visualizer/all). This code uses the MEMs microphone instead of the Sound Detector. It's not as fast since the code needs to take a sample of the audio and processes the DC offset audio signal. While the code isn't as efficient as using the Sound Detector's envelope pin, the code is sufficient enough.

_Note: It's better to use the MEMs microphone in a more quiet room with some sound. If there are active speakers being used, the MEMs microphone will be flooded with sound with this code. It was also better when the MEMs microphone was in an enclosure with no holes. It may be possible for the code to pick the beat better in the main `loop()` with a hole in the enclosure but it will require more testing._
