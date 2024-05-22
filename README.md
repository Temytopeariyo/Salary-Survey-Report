# Salary-Survey-Analysis Report

### Introduction

This report provides a comprehensive look into salary trends across various industries and job roles. By examining responses from a diverse group of professionals, the analysis uncovers key insights into average salaries, regional pay differences, and the impact of experience and education on earnings whin in turn helps both employers and employees make informed decisions regarding salary negotiations, career planning, and workforce strategies. This is going to be an interesting analysis because, it aims to uncover valuable insights and trends that lie within the data, shedding light on the dynamics of workers salary in relations to the industries, years of experience and location.

You can interact with the report [HERE]()


### Data Source
The data used for this project was from IJAN Tutor Dataset.

### Task
* Industry that pay Most: Analyze and compare average salaries across different industries and Visualize industry-wise salary distributions.
  
* Salary growth with years of experience: Explore how salaries change with increasing years of experience and Identify trends in salary growth over the years.
  
* Artist Most streamed track and total streams Correlation: Exploring correlations between tracks and number of streams.

* Top 5 most streamed tracks and the artists: Top N (5) most streamed tracks was recognised in relation to the artists.

* Playlist and Artist names: The distribution portray how spotify playlist affect Artist performance.

### Data Preparation and Transformation
To make ready dataset for the visuals, Excel was used to turn the unrelated sources of data into coherent, visually immersive, and interactive insights. In response to the given task, a careful assessment of the database table was carried out. Specifically, the database table was extremely dirty, hence calls for thorough cleaning. Some values were missing in some column but were replaced by 0 while many cells in some columns were also empty but were filled with NONE. 

The dataset was also imported to the power query for further cleaning afterwhich was closed and applied for visuals.


!(![image](https://github.com/Temytopeariyo/Spotify-Music-Analysis/assets/81833143/ba0e30f8-70fb-4623-8c19-bcab0f926ebd)

the above was marked as date table afterwards and created as measures with 
• Year-to-Date (YTD) Total streams
• Month-to-Date (MTD) Total streams
• Year-over-Year (YOY)Total streams. 
These measures became the central point where all the other informations related to Date in our analysis could link to. By using specific measures from this table of dataset, we established connections to other related distributions. 

### Data Modelling
Since I have establised another table, the logical representation of how data is structured and related within the tool and the collection of tables and relationships between them that are used to create reports and visualizations was necessary, hence the intergration of tables was involved (one to many)


!(![image](https://github.com/Temytopeariyo/Spotify-Music-Analysis/assets/81833143/55a3d484-dd97-46f6-987d-db12fe15acda)


### Data Exploration and Visualization
As the data was structured, All related calculations that would help the analysis were amde. These calculations included key measures from this dataset and the following measures were created for easy visualizing under calender: Day of week, Month Name, Quarter and Year. These measures became the central point where all the other informations in our analysis could link to. 


!(![image](https://github.com/Temytopeariyo/Spotify-Music-Analysis/assets/81833143/62b35309-21fc-4b96-813b-46a0ec9e9b9e)


### Sales Report - Visualization
I used PowerPoint to create the Canvas Background and during the visualization process, a comprehensive overview of total streams, tracks and average streams were provided through an information cards. The measures were dragged and dropped into these information cards and the total streams, tracks and average streams were all showcased. To enhanced analytical exploration, slicers were introduced, allowing for focused drill-through. These slicers that comprises Tracks, Date range, and Artist facilitated more targeted analysis. The online stream report was differenciated in terms of streamed by released date, Monthly streams, all tracks daily streams, artist most streamed track, Top 5 most streamed tracks and spotify playlist by artist name with the use of navigation button.


Recognizing the potential need to address questions related to fans stream as it relates to different year, I implemented a navigation button. This button enabled a seamless transition to an analysis centered on Total streams, addressing a specific aspect of the data for a more comprehensive perspective. The visual reports in terms of both total streams and respective years as shown below:

!(![image](https://github.com/Temytopeariyo/Spotify-Music-Analysis/assets/81833143/dd7456b9-8cc6-4b3a-a5f8-0a00d760f8bf)

Within the tracks performance report, a range of visualizations were constructed to illuminate various aspects. Firstly, a visual depiction total streams in relation to yearly performance that was generated, shedding light on how music were streamed in different year. Similarly, separate visuals illustrated the correlation between online streams, monthly, and daily streams performance were showcased, offering distinct insights.The visual report is shown below:

![image](https://github.com/Temytopeariyo/Spotify-Music-Analysis/assets/81833143/15e834ce-e687-4a81-be54-cacaeae9f9f1)

Incorporating the slicers enhance navigation that helps us differentiate each tracks, related period, and performance within period. 

You can relate with the report [HERE]()

### Insights and Recommendations
The top artist, based on their tracks streaming performance online, play a vital role in boosting the entertainment industry insights. These high-value fans that stream the tracks likely possess considerable listening taste as it relates to songs danceability, valence, energy,	acousticness,	instrumentalness,	liveness and speechiness.

My analysis covered a range of intriguing stream trends. The total streams across all tracks amounted to 489 billion with the total tracks of 952 with average streams of 514 Million. Based on the songs danceability, valence, energy,	acousticness,	instrumentalness,	liveness and speechiness, Blinding Light done by The Weekend has the highest streams and performed most from all the tracks released from 1930 to 2023. The analysis shows that Music Fans streams most on friday being the last workday of the week and the start of the weekend. More tracks were streamed in May but with an average stream of 415.67 Million, while January has 133 tracks streams with the highest average stream of 727.15 Million. This depicts that same tracks were streamed over and over again in January than May.

Lastly, the purpose of this analysis is to sensitize music artists on their tracks weakness, and improve their subsequent recording so as to attrct more streams and consequently promote their music career.
