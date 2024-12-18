# spark--indeed-scraping

This work is an extension from CISS - Company Diversity project (https://docs.google.com/document/d/16xLiBdAl6OwdoDekl4H0Rh99-y6ij9A5O-0P0bKLx3Y/edit?tab=t.0#heading=h.l4pps4i0h4ia)

The goal of this project is to see scraping recruiting websites to see if job listings contain any information for non-US citizens (i.e. international students, etc)
LinkedIn, Indeed, and Monster were chosen. 

The task was to see if scraping Indeed website is feasible.
Scraping Indeed is "indeed" possible, and the folder "IndeedJobScraper" contains files I found from a Reddit user's GitHub.
https://github.com/Eben001/IndeedJobScraper


There are all the functions for scraping in "job_scraper_utils.py."
The initial code scraped Link, Job Title, Company, Employer Active, and Location. 
I added an extra column for "Description" for description of the job.  
I have been trying to update "scrape_job_data" function so that it would scrape description of the job but have been unsuccessful.

I think you could start from here. If you could scrape description, it should contain information about international diversity (although with my own searching, description in general does not have any words about it most of the time). Or if you can find other ways to scrape information about diversity, that would do the job. 