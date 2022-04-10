# nocolor

This was made to quickly parse ansi color codes from text files.  If run without a parameter, it will look for a winpeas.txt or linpeas.txt file,
if one exists, it will parse that, otherwise it will exit.

If run with a parameter (or multiple parameters), it will cat out all the files in one stream with no ansi color codes (could be useful for things 
like autorecon output, etc)

For Winpeas/Linpeas, it will make a new file without ansi codes and name it winpeas.nc.txt or linpeas.nc.txt.

** To use: **

>sudo mv nocolor /usr/bin ; sudo chmod 755 /usr/bin/nocolor

** Examples: **

>nocolor ansiart.txt > asciiart.txt

>nocolor LinPEAS.output > LinPEAS.nocolor.txt

* Honestly, this was a 30 second bash file so this is kind of humorous, just figured I got tired of rewriting it trying different OS's =] *



