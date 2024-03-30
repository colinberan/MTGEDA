# Magic: The Gathering Exploratory Data Analysis

I’ve been a pretty avid Magic: The Gathering fan since high school and I recently came upon a great source of JSON files of what appears to be every single MTG card and set ever printed, so I couldn’t help but do an exploratory analysis of this data to see what kind of insights I could come up with just based on some questions I had.

Initially, my data didn’t have a release date for any of the cards on it, but I used a handy SQL query (also helpful for cutting out a bunch of columns that were either not useful for me or contained outdated or depreciated information) to join this data with a set that contained the release date for each set so I could have release date information for each card.

When going through this data I learned quite a bit and found some of my assumptions were true and some were way off. For instance, I took a look at the distribution of “color identity” among cards and found that, while I was right that the colors are fairly evenly distributed, the difference between the most populated single color (Green) and the least populated single color (Blue) was only slightly less than 500 cards over the course of almost 30 years of Magic. You can see the pie chart I made illustrating this below.
