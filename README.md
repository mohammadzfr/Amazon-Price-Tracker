# Amazon Price Tracker

This python script works by providing it with a link to a product.<br>
The script **parses the price of the item**, determines if it is **below a desired threshold**, and **alerts the user** of the price drop<br>

In this example, the script will be checking if the price of a [graphics card](https://www.amazon.ca/MSI-GeForce-RTX-3060-12G/dp/B08WPJ5P4R/ref=sr_1_12?crid=1O3VY85AZOS58&keywords=graphics+card&qid=1672890342&sprefix=graphics+car%2Caps%2C159&sr=8-12) drops below $500 CAD.

The script uses the following libraries and modules:

- **BeautifulSoup**: Parses data from the site
- **smtplib**: Handles email authentication and sends an email to the desired user
- **time**: Creates a delay before the program checks the page again
