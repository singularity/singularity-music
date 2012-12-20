Music for Endgame: Singularity

This is a git submodule of Singularity main repository found at:

http://code.google.com/p/endgame-singularity
https://github.com/singularity/singularity

The "music/" subdirectory of this package should be moved into your
Endgame: Singularity installation directory (if it does not already
exist). If this was downloaded as a git submodule then nothing needs
to be done, as E:S recursively looks for all "music/", "win/" and
"lose/" subdirectories inside the root "music/".  Any additional tracks
dropped in there will be played randomly as part of the soundtrack.

Note that Pygame support for MP3s is not as solid as its support for
Ogg Vorbis, and adding MP3s to the soundtrack may cause the game to
crash.  Removing any ID3 tags from the MP3 file may help. File formats
other than Ogg Vorbis and MP3 are not supported.

The "By-Product (Alternate).ogg" file is how By-Product song originally
sounded in earlier versions of E:S, which played the 44.1kHz file at
48kHz, thus slightly increasing its tempo and pitch. The file was later
fixed by properly resampling it to 48kHz to sound as author's original
intention, but as many players were quite fond of the faster version,
a 48kHz 'fake resample' version was also generated as an alternative.

Thanks to Max McCracken for providing these tunes!  They are
released under the same BY-SA 3.0 license as the Psycle and Renoise
source files for the tracks, which can be found in the main Endgame:
Singularity distribution.

See http://emhsoft.com/singularity/ for more.
