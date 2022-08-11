# dev-scripts

There is a set of useful scripts. 
Bash most of all. 
They are created for some reasons and may be suitable for somebody else.

You can put this scripts to directory `/.local/bin/` in your linux system and have fun.

#### Description of scripts

1. [git_clone](src/git_clone): clone repository and mark it as safe.
2. [switch_php](src/switch_php): switch version of PHP. (Use [Docker](https://www.docker.com/) instead of it when it is possible.)
3. [exif-gps-to-csv](src/file/exif-gps-to-csv): read `exif` part of media files and parse GPS data from it.
   Then expose data to console. There are columns: `file`, `latitude`, `longitude`.
4. [linebyline](src/file/linebyline): read text file line by line and expose content to the console. 