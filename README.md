# vocab2pdf
A bash script to create a multi-page PDF of words with definitions from a plain text list of vocabulary words.
dependencies: 
1) StarDict's sdcv (with WordNet dictionary) - WordNet dictionary in Stardict's directory (e.g. /usr/share/stardict/dic )
2) wkhtmltopdf - https://wkhtmltopdf.org/ 
3) zenity

Script tested with 800 words and used 3.2mb for temporary HTML files created. 
