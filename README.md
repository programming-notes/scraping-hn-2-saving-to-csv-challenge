# Scraping HN 2 Saving To CSV
 
##Learning Competencies 

* Map data in a file from one format to another using ruby
* Use the Nokogiri gem to parse CSS elements 
* Use the OpenURI built-in module to download and read live html pages
* Use Net::HTTP to download and read live html pages

##Summary 

 We're going to re-use your code to scrape Hacker News to save the data to a file suitable for analyzing offline, e.g., by using Excel.


##Releases

###Release 0 : Saving to a CSV

Ruby comes with a [build-in CSV parser](http://ruby-doc.org/stdlib-1.9.2/libdoc/csv/rdoc/CSV.html).

Write code that dumps each comment from a Hacker News post to a CSV file.  It might work like this:

```ruby
$ ruby hn_scraper.rb http://news.ycombinator.com/item?id=5003980
Saved 5003980.csv...
```

The `5003980.csv` file should now be a valid CSV file containing one line per comment from the passed-in URL. 


<!-- ##Optimize Your Learning  -->

##Resources