Python URL Shortener
This is a  URL Shortener which I developed using Python. This project will allow the users to generate short url,display the short url,open the browser page for the long URL by entering the short URL , and retreiving and displaying the short and long URL mappings. 

FEATURES OF THE PROGRAM:
-->Generates a unique short URL for a long URL
-->Validates the URLs before storing them
-->Opens the original URL using its short URL
-->Displays the original URL associated with a short URL
-->Displays all stored URLs
-->Stores URL data using a text file
-->Prevents duplicate short URLs
-->Contains a simple menu-driven interface

HOW IT WORKS
The program assigns a unique short URL to each long URL.
For example:
Long URL:
www.google.com
Short URL:
abc111

The mapping between the short URL and the original URL is stored in a text file:

abc111----------->www.google.com

When the program is run again, it reads the existing file , without erasing the existing data, and continues generating new short URLs.

CONCEPTS USED:
-->Python
-->File Handling: for appending,writing,reading the mappings and data stored in the text file
-->urllib.parse: for validating the URLs
-->webbrowser: for opening the URL


Files Created:

url_shortener.py
Contains the main Python program and all URL-shortening functionality.

fileurl_a.txt
Stores the generated short URLs along with their corresponding long URLs.

README.md
Contains information about the project and instructions for using it.

Menu Options

The program provides the following options:

1) Generates a short URL from a long URL
2) Opens a long URL(in browser) from a previously given short URL
3) Displays the long URL from the short URL
4) Displays all the URLs
5) Exit

How to Run
Make sure Python is installed on your computer.
Clone or download this repository.
Open the project folder in your terminal or IDE.

HIGHLIGHT:The project uses a text file instead of a database to store URL mappings.

Each entry follows the format:

short_url----------->long_url

This allows the program to retrieve previously stored URLs even after it is closed and reopened.

Future Improvements

Some possible improvements include:

Using a database instead of a text file
Creating a web-based interface
Generating random short codes
Adding expiration dates for short URLs
Adding click statistics
Improving URL validation

Author

Anjali Garg
