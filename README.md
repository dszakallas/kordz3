:star: kordz3 :star:
======

Kordz3 M4L Effect

Copyright (C) 2015  Dávid Szakállas

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.


Motivation
----------

I needed a way to map chords to my Launchpad to play in user1 mode. The idea was simple: before performance I would map some chords to a few consecutive pads, save them as a preset then play them on stage.  Initially, I tried to use the Schwarzonator2.0 M4L device by Henrik Schwarz (https://www.ableton.com/en/packs/schwarzonator/), but I had a hard time recalling saved presets with its external storage system. It stores the presets in a coll object and saves them to a text file, so its inelegant as you cannot drag and drop presets using Live’s internal file chooser. To make matters worse, it won’t recall automatically the last active preset when the device’s state is restored. Then I tried something simpler and turned to the simplest of devices,  the internal ‘Chords’, but that was a pain to map… turn every encoder for every freaking additional note to the right position and save them one by one. So I ended up creating my own one.

Features
--------

- map chords to 8 banks using the mouse
- play a chord by hitting a single note
- current preset is automatically saved with your Live set
- save presets with the ‘Save Preset’ button on the device title bar

Prerequisites
------------

- Ableton Live 9
- Max For Live

How-to
-----

- install: copy Kordz3.amxd to ‘user_lib/Presets/MIDI Effects/Max MIDI Effect‘ where user_lib is your Ableton User Library folder.

- use: search for Kordz3 in Live then drag and drop it before your instrument. To assign a chord to a bank, click on the number of the bank then input the notes with your mouse on the screen. To end modifying, click on the bank once again. To modify another bank, click on the other bank. Incoming notes from C1 to A1 will trigger output. Kordz3 starts numbering banks from 36 (C1). If you would like to use a different pitch, place a ‘Pitch’ MIDI effect before it (or edit the patch :smile: ).

License
-------
Please consult LICENSE file.
