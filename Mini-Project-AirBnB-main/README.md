# AirBnB Pro
<img width="557" alt="Logo" src="https://user-images.githubusercontent.com/64835443/138049488-45099acc-b166-4c99-bf6d-8399f7cd2283.png">

#### The only proffesional you need for all your AirBnB deeds.
Planning for a "Stay-Cation" but don't know the perfect place that will give you the homely feel and also fullfill your tourist needs? <p>
***AirBnB Pro*** is all you need.
<p>

**AirBnB pro** provides you with a recommendation engine and dashboard, where you can specify everything you want to consider before booking your AirBnB. You can filter by price, property type,
nearest tourist attractions and much more. 
<p>

## Recommendation Engine 

![Recommendation engine](https://user-images.githubusercontent.com/64835443/138058159-a777ce85-60f4-4425-a4c1-5bbe97411f78.gif)

Want to stay near the nature, beside a farm ? **De Baarsjes - Oud-West** is the best neighbourhood for you.
Be it staying near the metro or farm or art galleries our recommendation engine will find the best neighbourhood for you.

## Dashboard

![Dashboard (1)](https://user-images.githubusercontent.com/64835443/138060778-8b5c60d6-b3c4-4bf3-973f-338f4afe90c5.gif)

Whether you are a foodie or an art lover our interactive dashboard will help you identify the best possible AirBnBs according to your needs. You can choose from a wide range of features like price per night, nearest attractions,
distance from the city centre and so much more. We have made our dashboard user friendly so you don't have to waste much of your precious time in finding the perfect "home away from your home".
  
Link to Dashboard -  https://rb.gy/ubs4f9
## Journey to the Centre of AirBnB Pro
- *Data*
  <p>
    
    For a data science project, data plays an essential role as it helps in understanding patterns, trends and help procure important information for our project through it. The data source should be reliable and provide accurate or near to perfect statistics for a good recommendation engine. For this project the data has been sourced from - http://insideairbnb.com/get-the-data.html for the **Amsterdam** city.
    Our dataset can be found here - https://rb.gy/6jclvb
- *Dependencies*
    - Numpy
    - Pandas
    - Seaborn
    - Sklearn
    - Matplotlib
    - Folium
    - Geopandas
    - Plotly
    - Cufflinks
    - Nltk
    - Cleantext
    - Spacy
    - Pickle
    - Wordcloud
    - Tableau
- *Data Cleaning*
    
    Data cleaning is one of the initial steps in a data science project. It is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or missing data withing our dataset. For our project not a lot of data cleaning was required as the data used is from reliable source and did not contain any missing data.
    The data cleaning steps establsihed in this project include 
    - Dropping neighbourhood_group - *Empty Column*
    - Removing "%" from host_response_rate
- *EDA*
    
    Exploratory Data Analysis helps us understand data more thoroughly and helps draw effcient conclusions regarding our dataset. It helps us summarise our data and helps to think about how to approach our data. Visualization plays an essential part in this step. It helps us understand data visually and helps create insights more efficiently .
    For this project we have used many visualization tools like folium, plotly and matlplotlib for creating beautiful and eye-catching visualizations.
    - No. of listing by neighbourhood
    
    ![4546de6b-49c4-46c2-8706-3c76375f931a](https://user-images.githubusercontent.com/64835443/138214510-abb8a4f5-456f-4e07-9e90-a0e311dd45ba.png)
    
    It can be observed that most of the lisitings are situated in *De Baarsjes - Oud-West*
    
    - Visual representation of neighbourhoods on map
    
    ![Map](https://user-images.githubusercontent.com/64835443/138215346-b5191a86-9de9-44ba-826f-371cbac8b119.gif)
    
    - Comparison of property types of AirBnBs
    
    ![types](https://user-images.githubusercontent.com/64835443/138215645-a1ab30c9-0a68-4539-a26f-bc3ba6555995.png)

    We can observe that *apartments* are the most popular type
    
    - Side by Side visualization of reviews and average price for a 2 persons accomodation
    
  ![review price](https://user-images.githubusercontent.com/64835443/138216163-b79bebae-405f-4b67-bb82-8fc198bdad81.png)
    
    It can be observed that *Centrum-West* has the highest review score and also the highest average price. 
    
    - Visualizing average scores of different categories of reviews
    
    ![AvgOfReviews](https://user-images.githubusercontent.com/64835443/138217157-cff7a63f-bc9c-4069-950b-c6f9767f00d6.png)
    
    - No. of listing by superhost
    
     "**Superhost**" is the designation given to a host that has got good reviews consistenly by its guests.
    
    ![Superhost](https://user-images.githubusercontent.com/64835443/138217504-7a880166-583f-41bd-af7b-6c8337207eb8.png)

    - No. of Listing available by date
    
    ![newplot](https://user-images.githubusercontent.com/64835443/138218027-ce860ab1-2b5d-4e93-bf4b-08bcb6667862.png)
    
    - Average price of available 2 persons accommodation by date
    
    
    <img width="694" alt="AVGPrice" src="https://user-images.githubusercontent.com/64835443/138218547-07ab5d87-6f63-49c5-983c-ff4e85d6def8.PNG">


- *Word-Cloud creation*
    
    A Word-Cloud is the visual representation of words. The more frequently a word is used the more prominant it is.
    For this project word cloud has been generated using reviews.
    
    - Word-Cloud for reviews of all AirBnBs listed in Amsterdam
    
    ![WordcloudAll](https://user-images.githubusercontent.com/64835443/138219210-46ef2553-d21b-48bd-aa40-f17763243320.png)
    
    Words like *apartment*, *stay*, *great* and *Amsterdam* are the most prominent and hence most used in the reviews. This gives us an idea that apartments are the most popular type in Amsterdam and people have regarded it as a great place to stay.
    
   #### Wordcloud can also be generated for reviews for a specific neighbourhood.
    
    - Word-Cloud for Gaasperdam - Driemond
    
    ![Gaasperdam - Driemond-WordCloud](https://user-images.githubusercontent.com/64835443/138219978-1d180ad1-2d73-4662-a414-e23e62ae6506.png)
    
    - Word-Cloud for Centrum-West
    
    ![Centrum-West-WOrdcloud](https://user-images.githubusercontent.com/64835443/138220091-7fc87fbe-5376-4a86-9a00-353e172878fb.png)

<p>

- *Recommendation Engine*
  
  Finally a text-based recommendation engine using NLP was built to help find the best suitable neighbourhood.
  
  Steps taken in this process :
  - Conversion of text to word vectors
  - Training of a classifier model
  - Creating recommendation engine
  
- *Dashboard*

  The dashboard created helps user easily identify the area and narrow-down to their favourable stay by using interactive user-interface. The dashboard conatins an interactive map and toggles to choose from , like restaurants, museums, parks, clubs and shopping places. You can also find the nearest 10 attractions, with respect to the place selected. It also allows you to choose your property type and narraw down options by inputting average price.
