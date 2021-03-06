# Udasty-Wrangling-and-Analyzing-Data
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively for you to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.
# Software Needed
1/Need to be able to work in a Jupyter Notebook.

2/The following packages (libraries) need to be installed:
pandas.

NumPy.

requests.

tweepy.

json.

# Enhanced Twitter Archive
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though: each tweet's text, which was used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive "enhanced." Of the 5000+ tweets, tweets with ratings only have beenfiltered for (there are 2356).

# Additional Data via the Twitter API
Regarding the basic-ness of Twitter archives: retweet count and favorite count are two of the notable column omissions. Fortunately, this additional data can be gathered from Twitter's API. The project queries Twitter's API to gather this valuable data.

# Image Predictions File

Udacity ran every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

# Key Points

Key points to keep in mind when data wrangling for this project:

1/The project only need original ratings (no retweets) that have images. Though there are 5000+ tweets in the dataset, not all are dog ratings and some are retweets.

2/Assessing and cleaning the entire dataset completely would require a lot of time, and is not necessary to practice and demonstrate your skills in data wrangling. 

3/Therefore, the requirements of this project are only to assess and clean at least 8 quality issues and at least 2 tidiness issues in this dataset.

4/Cleaning includes merging individual pieces of data according to the rules of tidy data.

5/The fact that the rating numerators are greater than the denominators does not need to be cleaned. This unique rating system is a big part of the popularity of # WeRateDogs.

6/The project does not require gathering tweets beyond August 1st, 2017.

# Project Details

The tasks in this project are as follows:

1/Data wrangling, which consists of:

   Gathering data (downloadable file in the Resources tab in the left most panel of your classroom and linked in step 1 below).

   Assessing data.

   Cleaning data.

2/Storing, analyzing, and visualizing your wrangled data

3/Reporting on:

   Data wrangling efforts.

   Data analyses and visualizations.

