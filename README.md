# Amazon Price Tracker

This python script works by providing it with a link to a product. 
The script parses the price of the item, determines if it is below a desired threshold, and alerts the user of the price drop

The script uses the following libraries and modules:

- **BeautifulSoup**: Parses data from the site
- **smtplib**: Handles email authentication and sends an email to the desired user
- **time**: Creates a delay before the program checks the page again
