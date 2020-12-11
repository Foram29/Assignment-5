# Assignment-5

Here, I Want to explain whole pyhton code.

# Imported required libraries
import pandas as pd
import numpy as np

# Read the csv file 
youtube_df = pd.read_csv("youtube_dataset.csv", encoding="windows-1252")

# you can see the data 
youtube_df.head()

# you are able to see the information about the whole dataset
youtube_df.info()

# save the 1000 rows from the dataset which is saved in new varibale  
youtube = df.iloc[:1000]

# you can see the data by calling just function name
youtube

# calculate the distribution of channeltype from the top 1000 records.
youtube['channeltype'].value_counts()

# can save the 1000 rows in the new varible which will create the csv file in respective folder as used the function of pandas of DataFrame.
new_df=pd.DataFrame(youtube)
new_df.to_csv("youtube_1000.csv", index=False

# can see the 1000 rows
new_df.head(1000)
