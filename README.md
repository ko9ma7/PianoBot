## PianoBot
This is a bot that plays "Piano Tap Tiles 2" on an Android Emulator running on a Windows machine.

The method it uses is pretty simple:
- make a screenshot of the predefined area (needs to be specified when compiled in PianoBot.h)
- tap the black pixels in the predefined positions (positions get calculated from width, height, x and y position of window)
- if there are any baloon pixels at position x and position y, stop the loop
- else: repeat

It was created in about 2 hours. (C++ backend of getting and analyzing pixels was 99% of the work)

## Results

<p align="center">
  <img src="your_relative_path_here" width="350"/>
  <img src="your_relative_path_here_number_2_large_name" width="350"/>
</p>
