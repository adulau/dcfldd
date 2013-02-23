dcfldd
======

dcfldd is a modified version of GNU dd.  The major features added
are hashing, fast disk wiping (through patterns) and status output.

dcfldd was originally created by Nicholas Harbour from the
DoD Computer Forensics Laboratory (DCFL).  Nick Harbour still maintains
the package, although he is no longer affiliated with the DCFL.

Send any feature requests or ideas to the author at
<nicholasharbour@yahoo.com>.

dcfldd on GitHub
----------------

On https://github.com/adulau/dcfldd/, this is the latest version of
http://dcfldd.sourceforge.net/ (1.3.4-1) including Debian patches and
some additional patches from Alexandre Dulaunoy https://github.com/adulau.

dcfldd usage
------------

    dcfldd if=/dev/sda hash=md5,sha256 hashwindow=20G md5log=md5.txt sha256log=sha256.txt \
           hashconv=after bs=512 conv=noerror,sync split=20G splitformat=aa of=sda.dd
