# Webscraping the Yacht Marketplace  

This project retrieves yacht listings from [BOAT International](https://www.boatinternational.com/) and cleans the data so that it can be easily analyzed. You can read a little about the process in the [HTML report](/docs). 

### Notes

**get_yachts.R** and **yacht_market_report.Rmd** perform the exact same scraping task, but yacht_market_report.Rmd generates an HTML file.  

If you don't want to wait for the scraping to complete, or the script no longer works, you can also load the [RDS object](/data) (scraped 14. December 2020) into an R session.  

### Sample Viz

![yacht_hist](/images/yacht_age_histogram.jpg)
