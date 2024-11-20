AnyScrape
AnyScrape is a simple Python library that allows you to scrape headlines, links, and images from any webpage with just a single line of code. It's perfect for quick and easy web scraping without the need for extensive setup or configuration.

Features -
Scrape headlines from a webpage.
Extract all links (URLs) present on a webpage.
Retrieve the image URLs from a webpage.
Minimal setup and easy-to-use interface.

Installation
Install AnyScrape from PyPI using pip:

pip install AnyScrape

1. Basic Usage
Import the library and use the AnyScrape.scrape method to scrape your desired data.
HOW TO IMPORT?
WRITE-

from anyscrape import AnyScrape

# Scrape headlines
headlines = AnyScrape.scrape('https://example.com', target='headlines')
print("Headlines:", headlines)

# Scrape links
links = AnyScrape.scrape('https://example.com', target='links')
print("Links:", links)

# Scrape images
images = AnyScrape.scrape('https://example.com', target='images')
print("Images:", images)

Target variables-
'headlines': Extracts all headlines (<h1>, <h2>, <h3> tags).
'links': Extracts all hyperlinks (<a> tags with href attributes).
'images': Extracts all image URLs (<img> tags with src attributes).

Output:

Headlines-

Headlines: ['Welcome to Example', 'About Us', 'Our Services']

Links-

Links: ['https://example.com/about', 'https://example.com/contact']

Images-

Images: ['https://example.com/image1.jpg', 'https://example.com/image2.png']

Authors
Diksha, Ayush Kumar Verma
diksha260303official@gmail.com , vermaayush5535@gmail.com