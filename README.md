sci-hub python-script
[![Python](https://img.shields.io/badge/Python-3%2B-blue.svg)](https://www.python.org)<br>
=========
## First of all, thanks original author: zaytoun! 
Thanks for the amazing api of sci-hub used python.(https://github.com/zaytoun/scihub.py)<br>
I used Python to modify the API of the following zaytoun, and by my edit:<br>
It is very convenient to use "original web site or doi" as input to modify paper_url.<br>
It just need to change the inside the file when you begin to use, so as to facilitate mass download.<br>
## For example:
Open sci-hub.py and input the paper(DOI|PMID|URL) whatever you want to download.
```
paper_url=('QQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQQ',
            'XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX',
            'AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA'
           )
```
## Requirements
```
beautifulsoup4
requests
retrying
pysocks
```
