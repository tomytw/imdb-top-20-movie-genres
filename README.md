# IMDB Top 20 Genre Word Cloud in the 2010s (2010 - 2019) Visualization
Using pandas, matplotlib, wordcloud

I filtered the dataset according to my assumptions of a 'decent movie'. These are the filter conditions:
- Average rating >= 6.8 (upper quartile)
- Number of votes >= 1766 (upper quartile)

The frequency of each genre from the filtered dataset is divided by the total frequency of that genre from the unfiltered dataset. 
It simply means, the probability of a better rated movie is proportional to the size of the genre in the word cloud.
