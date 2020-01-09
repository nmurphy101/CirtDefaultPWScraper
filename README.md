# Cirt-Default-PW-Scraper
Scrapes the Cirt.net site of all of the default passwords listed and outputs into a file.


Created by: Nicholas Murphy
     email: nick.murphy@mnsu.edu
************************************************************************************************************************************
Install:
Just run the script in a terminal and it'll generate a file containing the default passwords and a log 
detailing if anything major happens all in the same directory as the script.

Run with:
$ apt-get install python3-bs4 
  or
$ easy_install beautifulsoup4
  or
$ pip install beautifulsoup4
  
  then
$ python3 scrape_default_pw.py 

************************************************************************************************************************************
NOTE:
The passwords scraped also include password "placeholders" (i.e. "123 (or blank)" or "(see note)") and thus aren't passwords.
These would potentially need to be removed or replaced to have a more accurate list.

************************************************************************************************************************************
