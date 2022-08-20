# we_rate_dogs
This project was done by carrying out wrangling process which involves gathering, assessing(visually and programatically) and cleaning data on a dataset which is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10.

In the Gathering Phase of the wrangling process, the data was gotten from 3 different sources 1.twitter_archive.csv which was already provided, and I loaded into a dataframe called twt_archive 2.a url which contains an image prediction dataset which I imported as tsv document using Twitter’s requests library and subsequently loaded as a img_predict dataframe using separator with ‘read_csv’ 3.an API dataset which was a JSON file was read into a twt_api dataframe using Python’s ‘read_json’

In the Assessing Phase and clceaning phases, each data set was visually and programmatically assessed for both quality and tidiness issues which were detected across the datasets, with copies of dataset created and cleaned:

The following insights were investigated and a visualization was made to corrobarate what dog breed was the most liked: 

 1. What dog breed is the most liked
 2. what dog stage is the most liked
 3. What dog stage is the most common


