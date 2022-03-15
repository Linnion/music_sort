# music_sort
Music Sorter v1.0

This script was made with the aim of sorting my mp3 collection into directories by artist name to allow it to be more easily interpreted by Plex.

Music files were originally stored in one folder and were named using the convention '[Artist] - [Title]'. This script can be dropped into the directory where the music is stored, and when run will create a directory for each artist, based on the file name, using ' - ' (space + hyphen + space) as a delimiter. Files are then moved from the parent directory into the artist directory. 

Any pre-existing directories and the script file itself will be ignored, however other files will be captured and processed. Script will attempt to create a new directory each time a file is processed, even if a directory with the same name already exist, printing an error message, however this doesn't seem to affect the functionality of the script. 

In the future, I hope to update the script to only process files of a particular extension (.mp3, .wma, etc) and to only attempt to make each directory once, reducing the number of errors printed.
