# Scholar_Scraper
## Introduction


Scholarly is a Python module that allows users to retrieve bibliometrics from Google Scholar. This script automates the process of scraping this information from Google Scholar using scholarly for a list of authors.

This project currently works with scholarly 1.4.5

## Installation and Setup


1. Upload this project in Syzygy.
  - Click the "+" button to open a new launcher and click "Terminal"
  - Type "git clone https://github.com/ubcbraincircuits/Google_Scholar_Test" and click enter
  - The file should now be in cloned in your directory.

2. Install scholarly
  - In the terminal (from above) type "pip3 install --user git+https://github.com/scholarly-python-package/scholarly.git" and press enter
3. Upload a .csv file with the list of author names. Author names should match their names in Google Scholar. This file should be in the same directory as this          notebook file.
4. Modify the names of the input/output files below (in step 1). The input file name must match the .csv file name.
5. Modify the "affiliations" variable as a list of institution names which the researchers are affiliated with. Include both abbreviated and long form.
6. Run all cells (click shift+enter to run a cell or the play button above).
7. Check for warnings in step 4 and make sure that the authors scraped from Google Scholar have the correct affiliation and are in fact the correct author. You may     need to change the names in the input csv file to match the author name on Google Scholar.
8. Find the output csv file in the same directory as this notebook file. You can check the last column of this file for warnings.
