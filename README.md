# companyparents
* Get data from wikipedia torrent dump
* cat /data/downloads/transmission/enwiki-20170320-pages-articles.xml.bz2 | bunzip2 | pv | grep -A100 'Infobox company' > infocompany
* process infocompany
* creates data2
* Cleanup
