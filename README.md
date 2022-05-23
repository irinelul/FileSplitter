# FileSplitter
This script will split a large text/csv file into multiple files, all with the same row count.
I am using a (rather powerful) chrome extension for web crawling that's able to take JSON as a sitemap (list of sites to be crawled)
However, it is limited to 10k websites per instance, as well as you must format the JSON in a particular manner.

This python script takes a list of websites as input, and will split the big list into however many files you want (e.g. let's say you have 40k websites, the script will ask you to enter how many rows you want per future file to be created, you will type 10000 and the end result will be 4 files of 10k websites each, all formatted accordingly and ready to be inserted into the extension).
![Splitter input](https://user-images.githubusercontent.com/16565764/169752906-26eb4949-c0c0-4e45-9c20-55940559ad3e.png)


This is very useful when dealing with large datasets, formatting 200k links to be able to split them up is difficult, this gets it done in a couple of seconds.

A rather pre-historic cmd box pops up, asking you to select the file (using regular windows explorer), as well as how many rows you want per file.
![UI](https://user-images.githubusercontent.com/16565764/169753022-c1bfdf5b-254e-4b80-a470-bf505cef0678.png)

Next, you select the folder where you want the files to be output and you begin naming each file's sitemap (every instance of crawling needs to have an unique ID)

![Result](https://user-images.githubusercontent.com/16565764/169753215-e0dd0fb2-d8ff-47b0-ab3f-a3af01216c1b.png)

After this, you have the files named accordingly, 0-250,250-500,500-750,750-1k as well as properly formatted, every line separated nicely and ready to be used.
