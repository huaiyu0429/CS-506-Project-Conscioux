# CS-506-Project-Conscioux Internet Market Research
## Project Goals
Our objective is to locate potential markets for Conscioux by taking insight of people's attitude towards veganism. To be more precise, we are interested in the supply and demand of vegetarian. To have a general view of how these tweets distribute across the country, we plot the coordinates of these tweets on Google Map. At the same time, we also visualize the distribution of restaurants that provide vegetarian food by clustering Yelp data. With the preprocessed tweets data, we build several models that classify the sentiment based on one's tweet and choose the optimal one with highest accuracy. To explore other factors that may affect people's attitude towards vegan, significant factors are achieved by logistic regression.
## Dataset
The two main datasets we use are the data containing terms "vegan", "weight loss" and "vegetarian" scraped from Twitter and public Yelp dataset. Because the original data containing information about tweets is too large to upload, here we only upload the csv after tidying. Our data file including 4 tweets csv files and 1 state_rank csv for lositic regression. The yelp dataset is too large and we cannot upload it. However, you can download the Yelp public dataset from [here](https://www.yelp.com/dataset).
## Quick Tour of Repository
There are one final report(pdf), 2 html (tweet & yelp heatmap), 5 ipynb files (tweets colllecting, tweets tidying, tweets analyzing & logistic regression, tweets heatmap, yelp clustering) and 1 poster(pptx).
## Pre-preparation for running the code
* Get your credentials and access token from your twitter account [here](https://www.slickremix.com/docs/how-to-get-api-keys-and-tokens-for-twitter/)
* Get your credentials and access token from your google map account [here](https://developers.google.com/maps/documentation/javascript/get-api-key)
* Replace your twitter keys in getdat.ipynb and google map keys in clustering.ipynb
* Install all packages we used in these files
### Feel free to ask us any questions: ynxie@bu.edu, huaiyu@bu.edu and kejiang@bu.edu
