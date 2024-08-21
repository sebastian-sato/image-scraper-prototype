# image-scraper-prototype
A program for scraping image links from the internet based on keywords in their alt texts. It is still very much a work in progress.

[generate-seed-urls.ipynb](generate_seed_urls.ipynb) is used to generate a text file containing all of the seed urls for the scraper, seperated by newlines, based on a query. An example seed-urls.txt is provided based on the query "dog".

[image-scraper.ipynb](image_scraper.ipynb) contains the code for running the scraper, in its current stage it is quite unreliable and error prone, but with the right amount of processing its results can still be useful.
