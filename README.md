# Airbnb NYC Listings - Exploratory Data Analysis | Python, Pandas, Matplotlib

**Business Context**
Since 2008, guests and hosts have used Airbnb to expand on travelling possibilities and present a more unique, personalised way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analysed and used for security, business decisions, understanding of customers' and providers' (hosts) behaviour and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.

**Problem Statement**
Analyse the listing data and find answer to below question to uncovers trends, patterns, user preferences and help business to make better decision for future.  
1.	Which major neighbourhood group is most popular for Airbnb listings?  
2.	How price varies as per the major neighbourhood group?  
3.	Which areas have highest number of listings?  
4.	How price varies as per the areas or locality?  
5.	Which type of rooms are available across the New York city?  
6.	How price varies as per the room type?  
7.	How price is spread over neighbourhood group based on room type?  
8.	How room type and price varies in different major neighbourhood group?  
9.	Which is the most preferred night stay?  
10.	How is the price distribution across all listing?  
11.	How the price varies in Manhattan as we go away from the finals district?  
12.	How the price where is across all listing as we go away from finance district?  
13.	How the price is affected as we go away from JFK airport in Brooklyn?  
14.	How price varies as the number of reviews of a listing increases?  
15.	How is the distribution of listing across all major neighbourhoods?  
16.	How is the distribution of price across various latitude and longitude?  

    
**Data Overview: -**
This data set contains around 49000 row representing individual listing on AirBnb site and has 16 columns as follows   
Id :- This is a unique identifier for each listing in the dataset.  
Name :- This is the name or title of the listing, as it appears on the Airbnb website.  
Host_id :- This is a unique identifier for each host in the dataset.  
Host_name :- This is the name of the host as it appears on the Airbnb website.  
Neighbourhood_group :- This is a grouping of neighborhoods in New York City, such as Manhattan or Brooklyn.  
Neighbourhood :- This is the specific neighborhood in which the listing is located.  
Latitude :- This is the geographic latitude of the listing.  
Longitude :- This is the geographic longitude of the listing.  
Room_type :- This is the type of room or property being offered, such as an entire home, private room, shared room.  
Price :- This is the nightly price for the listing, in US dollars.  
Minimum_nights :- This is the minimum number of nights that a guest must stay at the listing.  
Total_reviews :- This is the total number of reviews that the listing has received.  
Reviews_per_month :- This is the average number of reviews that the listing receives per month.  
Host_listings_count :- This is the total number of listings that the host has on Airbnb.  
Availability_365 :- This is the number of days in the next 365 days that the listing is available for booking.  


**Approach: -**
•	We first imported necessary libraries and then loaded the data set.
•   Using data wrangling operation this dataset was cleaned and outliers were removed for further analysis.    
•	Summarised the Data.    
•	Added a few extra columns based existing column, created small data sets with various groups and aggregated function applied on other columns.    
•	Choose the appropriate   chart or graph to find insights from data to answer question mentioned in problem statement.     
 
**Solution to Business Objective and Conclusion:-**
What do you suggest the client to achieve Business Objective ?   
•	We found that Manhattan and Brooklyn have the highest demand for Airbnb rentals in NYC, as more than 90% of listings are in these neighbourhoods. This makes them attractive areas for hosts to invest and list the property.  
  
•	Manhattan being major finance hub and having various tourist attraction, parks, important buildings, markets, island and also its substantial number of tourists throughout the year, it makes it the most in demand and expensive place for Airbnb rental properties. 
  
•	Brooklyn is second in most numbers of listed properties. But listings are cheaper prices as compared to the Manhattan: With most listings located in Williamsburg and Bedford Stuyvesant two neighbourhoods which are very close to Manhattan, hence tourists get the chance to enjoy both boroughs equally while spending less.  
•	Being close to Manhattan yet having cheaper rates, Williamsburg, Bedford-Stuyvesant, Harlem, Bushwick, and the Upper West Side are the most popular neighbourhoods in terms of listing counts, indicating strong demand for Airbnb rentals in these areas.  

•	Closer the property is to Manhattan most important places higher is the price This makes investing in property in Manhattan may be more lucrative for Airbnb rentals.  
  
•	As per the analysis most of the Airbnb rentals are preferred for short-term stays of 1 to 3 days and some for up to week.  
  
•	The highest listings on Airbnb are for entire apartments/home and Private Rooms being second and but just little less. But there are very few shared rooms listed. This suggests that travellers preferred to stay in stay in private since say is for very short.  
  
•	We also found that the availability of Airbnb rentals varies significantly across neighbourhoods, with some neighbourhoods having a high concentration of listings and others having relatively few.  
  
•	The neighbourhoods near the airport in Queens would have a higher average number of reviews, as they are likely to attract a lot of tourists or visitors who are passing through the area. The proximity to the airport could make these neighbourhoods a convenient and appealing place to stay for travellers for short-term stay with spending less money because the price distribution is high in Manhattan and Brooklyn.  
  
•	We also found for Manhattan and Brooklyn nearer the property to important places of Manhattan more is the price but in queens closer is the property to airport more is the price.  
  
•	We also noted highly reviewed properties have lesser price which indicates traveller do check for reviews and prefer cheaper rental properties.  
  

**Conclusion: -** Based on above finding Airbnb and property owner can invest the new property to get most income and can also suggest travellers’ best area for say to as per need and spending will.  

