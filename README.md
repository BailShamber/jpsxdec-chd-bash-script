# jpsxdec-chd-bash-script

**A bash script for loading .chd image files in jPSXdec.**

Requires Java.

Requires `chdman` provided by mame-tools in debian and ubuntu: `sudo apt install mame-tools --no-install-recommends`

Download either `jpsxdec` or `jpsxdec-ssd` from here and replace `"insert the path to the jpsxdec jar file here."` with the location of jpsxdec gotten from https://github.com/m35/jpsxdec

It works by converting the .chd image to bin/cue in the "/tmp" directory first then loading the bin file.

"jpsxdec-ssd" is an ssd (solid state drive) friendly version, it loads the image to ram instead of temp dir (in most linux distros).

**warning** "jpsxdec-ssd" needs alot of ram to work, 6gb recommended.
