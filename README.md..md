# Project: Wrangling and Analyzing Data

## Indroduction
In this project, we use real -world data and it inloves the flowwing process:
- Data gathering.
- Data assessment both assessing visual and programmatically
- Data cleaning which consists of quality and tidiness issues.

### Data Gathering
The Data sets used in the data wrangling project include twitter-archive-enhanced, image-predictions, and tweet-json. The twitter-archive –enhanced was provided by Udacity where we downloaded the manually into Juypter notebook. The URL for image –prediction dataset was provided by Udacity which was downloaded programmatically. Tweet-json data was dowloaded usig tweepy and json which were imported into juypter notebook. After downloading the JSON file, we use API which helps to read line by line for favorite_count, retweet_count, and tweet_id in the JSON file.

### Data assessment¶
The assessment of data was done visually and programmatically. Each data was displayed in the juypter which was manually assessed for quality and tidiness issues. However, assessing data programmatically, a function such as pandas was used to assess the quality and tidiness of the data. After assessing data visual and programmatically, the following issues of quality and tidiness were identified in three data sets:
- Some columns have repeated retweets rows in df1_archive enhanced data set
- Columns likes name,doggo, floofer, pupper, puppo contains None as missing values instead of NaN.
- Some names of dog in p1 p2 and p3 in image prediction data set start with small letters.
- The timestamp and tweet_id have wrong datatypes.
- The name column, contain letter a as the names of the dog
- The column of name should be replaced with name_dog to be meaningful.
- The url of source should not be anchored by html text.
- The tweet_idis duplicated in df_column
- The three datasets, such as df_tweet_json, df_image_prediction and df1_archive_enhancedshould be merged into one master dataset
- The doggo, floofer, pupper and puppo are stages of dog, therefore, they should be written as one columns knowns as stage_of _dog

### Data Cleaning
Before data cleaning, we make copies of the original data sets. Then, we address the quality and tidiness issues by defining, coding, and testing each of the addressed issues. The following are procedures how we clean data sets:
- Remove retweets rows from df1_archive enhanced data set
- Replace None of name, doggo, floofer, pupper and puppo with NaN as missing values.
- Start dogs' name with capital letter in image prediction dataset.
- Convert timestamp into timestamp datatype and tweet_id into string.
- Replace a with Alfie in archive enhanced data set.
- Change name to be name_dog.
- Replace url with text with the  sources.
- Drops columns with many missing values in df1_archive_enhanced dataset
- Replace repeated columns with one column known as dog_level
- Combine three data sets into one master dataset..
- Lastly, data was stored  into csv file in juypter notebook.

### Python libararies used for the project
- pandas 
- requests
- numpy 
- tweepy
- json
- matplotlib.pyplot



```python

```
