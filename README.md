# New-York-City-Airbnb
Diagnostics Analysis( why did it happen)

## About Dataset

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalized way of experiencing the world. This dataset describes the listing activity and metrics in NYC, NY for 2019.
This dataset is from [kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)

## Objective

Which hosts are the busiest and why?

## Data dictionary

Column Name		                  Description
id	        	                  A unique identifier for each listing.
name	                         	The name of the Airbnb listing.
host_id	    	                  A unique identifier for the host managing the listing.
host_name	  	                  The name of the host who manages the listing.
neighbourhood_group	          	A broader classification of neighborhoods (e.g., borough or region). Often used for larger cities.
neighbourhood	    	            The specific neighborhood where the listing is located.
latitude	        	            The latitude coordinate of the listing's location.
longitude	                      The longitude coordinate of the listing's location.
room_type	        	            The type of room being listed, such as "Entire home/apt", "Private room", or "Shared room".
price	            	            The nightly price in the local currency for the listing.
minimum_nights	  	            The minimum number of nights required for booking this listing.
number_of_reviews		            The total number of reviews the listing has received.
last_review	      	            The date of the most recent review. This is stored as an object (string) and may need to be converted to datetime.
reviews_per_month		            The average number of reviews received by the listing per month.
calculated_host_listings_count		The number of listings that the host manages.
availability_365		              The number of available days for the listing in the last 365 days.

## Process
1. ### Define the problem:
    The problem is to find the busiest hosts and find why the are busy. In the process i have to find the key metrics that affect it.
3. ## Collection of the data:
   The data was collected from kaggle. I used Kaggle api to connect it to my google collab using !pip install kaggle and also downloading the token on my google drive 
4. ## Clean the data:
   The are alot of null value and outlier in the data.
5. ## Analyse the data:
   -I identify the key metrics: calculated_host_listings_count, availability_365
   -Identify the busiest host
   -Visualizing busiest host
   -Analyze review frequency
   -
7. Use libraries to vizualize the data
## Tools and libary used
Google collab, python, pandas, numpy, seaborn, matplotlib



##
