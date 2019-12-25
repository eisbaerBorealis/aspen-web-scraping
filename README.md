# aspen-web-scraping
A python program to scrape the USU Aspen Bibliography

This program was developed with Thonny on Windows 7

## Instructions
* Install Thonny
* Go to Tools > Manage Packages
* Find and install the following packages:
  * beautifulsoup4
  * requests
  * lxml
* Alter the global variables in web-scrape.py
  * Change not_found to what you want the default value to be, for example:
    * 'Not found'
    * ''
    * '-'
  * Change filename to the desired output file name (ending with .csv)
* Run the program


## Notes
* When I ran this program, it took about 25 minutes to run through 5,923 webpages
* When I opened this in Microsoft Excel, it interprets some cells under Pages as dates, e.g. 1-2 becomes Jan-02
* I will research an Excel fix and post the instructions here