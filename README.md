# Data And Bagels
Some digital journalism tips and tricks (including some learned at NICAR17) for a quick talk at the University of Montana Journalism School 

#### First off: Download [this zip file](https://github.com/kaylarobertson3/Data-and-Bagels/archive/master.zip). If you want to stick around until the end for some very basic HTML / CSS, download the [Sublime Text Editor](https://www.sublimetext.com/).

![data](https://media.giphy.com/media/CFkeus3K7NXBS/giphy.gif) ![bagel](https://media.giphy.com/media/ORYgct7M6YynC/giphy.gif)

# A little about us

Claire, Kelsey, [Kayla](kaylarobertsondesign.com). 

# Data journalism glossary
Terms to know. Or, at least pretend to know and reference during job interviews.

1. term one
  * term one def
  
2. term two
* term two def 
  
3. term two
  * term three def
  
# So where do I find this "data" stuff?
Here's a few solid resources. Bookmark these to use as sources for stories, or search these for story ideas (look for outliers).

### [Data.gov](https://www.data.gov/)
All of the U.S. government’s open data. Nice, easy to use website. If you’re writing a story about climate change, you can easily search by that + Montana or U.S. to see what kind of data you need. From there, you download. 

### [Census American Fact Finder](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml)
Basically all of the census data. The website is super dense and not super intuitive, but it’s a goldmine of census info, which is great because historically the census is super accurate, recurring by year so it’s reliable, and great for demographic-based stories (race, age, ect). 

### [National Data Repository](https://en.wikipedia.org/wiki/National_Data_Repository)
Wikipedia page of data hubs of different countries that are government funded / based. 

### [Google Public Data Explorer](https://www.google.com/publicdata/directory)
Can help you visualize a dataset. Kind of like Google search, it searches open datasets. Doesn’t have everything and the search can be tricky. But it can quickly show you what a dataset has in it without you having to analyze it and make your own infographic. You can easily see if the dataset is worth downloading, etc. 

### General searching tips
The file types PDF and Excel are often where the good data is. To find these:
* Google search: missoula housing data filetype:pdf
  * Searches only PDFS with those keywords 
* Google search “montana meth project” filetype:xls 
  * Searches only Excel files with those exact terms
  
# Making your own data
Kelsey will tell you how to scrape the web! Whoo

# Ok, so I have this data. What can I do with it?
Infographics are cool and good. Why? Infographics make stories more believable, more shareable, and more digestible for audiences. How your story is presented online is everything. Here are some tools that reporters (or anyone) can use to make their stories better — no coding or design knowledge involved. Here's a few starter tools:

## [Datawrapper](datawrapper.de)

* ABOUT
Datawrapper is a simple chart and map making tool created by journalists and Germany. It's very user-friendly, mobile responsive and customizable according to your publication's style guide. It's also important to visualize any data you have, even if a chart isn't necessary for your story. Overall data literacy enhances a reporter’s bullshit detector. Additionally, by having a designer create this (very simple) chart for you, you’ve outsourced your story and possibly missed something important. So let's make a graph.
  
* TUTORIAL
  * First, find the file called POTUSTWEETS.csv in the folder you downloaded.
  * Clean data: only use numbers —  no dollar signs, percent signs or commas. Datawrapper will read this as a string! Append and prepend your data easily within Datawrapper after you’ve uploaded it.
  * Note section is great for transparency, esp. If you have a pie chart that adds up to more than 100%. Explain the study.


## [Knightlab tools](https://knightlab.northwestern.edu/)
Knightlab is a leading innovator in journalism technology, and makes a lot of opensource (free) resources for journalists. There are three main tools which are very usable, responsive and easy to learn. Let's look at how to make an interactive timeline:

### [Timeline.js](https://timeline.knightlab.com/) 
* What it is: Open source tool for making interactive, responsive timelines.
  * Cool because: Can import content from Twitter, Flickr, YouTube, Vimeo, Google Maps, Wikipedia, SoundCloud. Responsive on all devices, pretty easy to use. 
* How to do it:
  * Timeline.js uses Google Sheets. [Click here to get the template](http://timeline.knightlab.com/#make) and follow along.
     * Click Make a Timeline. Click Make a Copy. *important: Don't change the column headers, don't remove any columns, and don't leave any blank rows in your spreadsheet.* 
     
  * It may look daunting, but all the hard Excel work has been done for you. Just fill in the columns with your information. I’ve taken the data Kelsey scraped (POTUS tweets from March). I’ll do the last few lines to show you what I did. (Feel free to make your timeline based on anything — fake dates, your life events, ect. for). 
  
  * Input each day, month and time into separate columns. Add a headline for the slide and add your body text. Options: Links to media (must copy image address for photos. Must be hosted somewhere online) This is also where you add Soundclouds, embed codes, ect. 
  * Each downward row (1, 2, 3, 4) will be a different ‘slide’ with a different headline and visual and date.
  * When you’re done: File, publish to the Web. Click OK. Yes, you are sure. 
  * Now, copy the URL it gives you.
  * To generate the timeline, go back to Timeline.js website (https://timeline.knightlab.com/#make). Paste the code you copied into step 3. 
  * Here you can preview, change a few settings, and grab the iframe code to publish to your site!

## So much more you can do with data — bookmark these: 
 * [DataViz Catalogue](http://datavizcatalogue.com/) — A resources that lets you search by both the type of chart and by function of what you want to show based on your dadta. Then it recomends websites and tools of how to make them, and tips on what kind of data fits best. Nice. 
 
 * [RAW Graphics](http://rawgraphs.io/) — another cool infographic-generator to check out. 
 
 * [Here's a full list of opensource resources from JournoCode](http://journocode.com/data-journalism-tools/)

# Bots 
![chatbot](https://media.giphy.com/media/NHIecaiSc7YjK/giphy.gif)

# HTML/CSS: Or, how do these things get published?
Remember that .zip folder we downloaded at the beginning?

* Want more? [W3Schools](https://www.w3schools.com/) Is a leading web resource with how-tos on just about everything web design.
