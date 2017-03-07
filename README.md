# christmas-lights-2016
(Yeah I just need a place to store backup code k thx.)

This was a small project to create an Arduino controlled light show on a large Christmas tree.
[![ScreenShot](http://img.youtube.com/vi/_yvnFnd9enA/0.jpg)](https://youtu.be/_yvnFnd9enA)

The music syncing process took several stages:
1. Determine the BPM of the music .mp3 file.
2. Create a txt file denoting times and beats for light start times and durations.
3. Run a compiler script to turn the lightmap into exact time in seconds, using 0s and 1s for lights turning on and off.
4. Use the final runtime script to read the compiled txt and send strings to the Arduino.
