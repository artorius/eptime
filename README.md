# eptime
A utility to search library and update .nfo files with correct runtime for tv episodes.

NOTE:  You must have a properly formatted .nfo file for your TV shows already.  These
can be easily generated from exporting your library through Kodi.

This script will use ffprobe (from the ffmpeg project) to determine the duration
of your video files and update the .nfo file for that episode.

Future versions will include commandline options and the ability to update a centralized
MariaDB/MySQL databases with the correct runtime per episode as well.
