This script takes a list of words (single column in plain text format) and produces
a pdf with an entry per page as well as a text file with the words and their definitions.

Dependencies: StarDict's sdcv (with WordNet dictionary), imagemagick, and zenity
StarDict package available at http://stardict-4.sourceforge.net/

WordNet dictionary in Stardict's directory (e.g. /usr/share/stardict/dic )
for more info visit: https://owenh.net/stardict.html
dictionary also available here: 
http://www.atadcrazy.net/gnu-linux/misc/stardict_wordnet.tar.bz2

Script includes feature to format the list in alphabetical order and remove duplicates
Note: Tested with 8000 words. The sleeps may need to be increased if the entry word list is larger. 
