# jpsxdec-chd-bash-script

**A bash script for loading .chd image files in jPSXdec.**

Requires `chdman` provided by mame-tools in debian and ubuntu: `sudo apt install mame-tools --no-install-recommends`

It works by converting the .chd image to bin/cue in the "/tmp" directory first then loading the bin file.

"jpsxdec-ssd" is an ssd (solid state drive) friendly version, it loads the image to ram instead of temp dir (in most linux distros).

**warning** "jpsxdec-ssd" needs alot of ram to work, 6gb recommended.
