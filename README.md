# FileSplitter
This script will split a large text/csv file into multiple files, all with the same row count.
I am using a (rather powerful) chrome extension for web crawling that's able to take JSON as a sitemap (list of sites to be crawled)
However, it is limited to 10k websites per instance, as well as you must format the JSON in a particular manner.

This python script takes a list of websites as input, and will split the big list into however many files you want (e.g. let's say you have 40k websites, the script will ask you to enter how many rows you want per future file to be created, you will type 10000 and the end result will be 4 files of 10k websites each, all formatted accordingly and ready to be inserted into the extension).

This is very useful when dealing with large datasets, formatting 200k links to be able to split them up is difficult, this gets it done in a couple of seconds.
