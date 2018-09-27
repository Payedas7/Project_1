--------------------------------
# Project_1 - Team_8
--------------------------------
# Project Name: “Video Game sales analysis”
--------------------------------

Project Members:  Payel Das, Monisha Jain


Project Description: 
As much as video games are immersive and entertaining, video games are also a business and thus follow the rules of a business. This comes into play when seeing that major publishers who have more resources to put into marketing the video games during release dominate sales in all regions. We can also see that certain regions prefer certain genres of games as well as that the rating of a game can determine the sales quantity.

The objective as always is to hone my skills as a data analyst with this data we will research if there were correlations between the number of sales affected by publisher, country, release years, critic scores, user scores, game genre and game maturity rating. The motivation of this project to visualize the data set and practice exploratory analysis of data set.

In this project we are going to find the most significant factors that contribute to the sales of a video game would consist of a multiple of variables. These such variables are the publisher, platform, genre, rating, and region and after comparing data from sales in each category we were able to conclude that these factors were the most influential.

Though we can predict that outcome of sales to a certain degree with the categories we have mentioned above, we must also conclude that to create a successful video game the game itself must come into play. A videogame will not be successful if it fits all the popular categories of a specific region but fails to live up to be a quality product that entertains the consumer; after all the purpose of a video game is to entertain and immerse a consumer into enjoying the product.
 
Research Q&A:

When we were first told to search for a data set that we could analyze on our own, the first ideas that came to our minds revolved around all our interests. We had multiple ideas, but none that we all could agree upon. That is until a few researches and we found a subject matter that we all mutually enjoyed. That subject was video game. We realized that when we all first started our journey in computer science we always dreamed about making our own games. With that in mind, we searched for data sets involving video games.

The data to be used is from Kaggle user Gregory Smith and it has sale records of sixteen thousand different titles. With this data we used it to research if there were correlations between the number of sales affected by publisher, country, release years, critic scores, user scores, game genre and game maturity rating. The following are the questions we wished to answer by leveraging the wonderful python libraries for data analysis and data visualizations:

1. For a genre of games, what variable helps make the most sales?
2. What are the rankings of game genres within a certain nation?
3. In the past five years, what genre of games has been gaining more popularity?
4. What game has the highest sales in the world and what are its sales within multiple nations?

Some areas worth exploring:
•	Titles which are available for more than one platform
•	Top contending platform
•	Which type of platform is popular?
•	Top selling genres
•	Top publishers by Global Sales


Datasets:
The dataset came from Kaggle.com and can be found here. The set includes a list of games with sales greater than 100k copies (roughly 16,500 rows) and was scraped by Greg Smith.
The file we are going to work with is CSV formatted and the Data fields are as below:
•	Name		-  The games name
•	Platform   	-  Platform of the games release (i.e. PC,PS4, etc.)
•	Year_of_
Release 	-  Year of the game's release
•	Genre   	-  Genre of the game
•	Publisher   -  Publisher of the game
•	NA_Sales 	-  Sales in North America (in millions)
•	EU_Sales 	-  Sales in Europe (in millions)
•	JP_Sales 	- Sales in Japan (in millions)
•	Other_Sales -  Sales in the rest of the world (in millions)
•	Global_Sales-  Total worldwide sales
•	Critic_Score-   Aggregate score compiled by Metacritic staff
•	Critic_Count-    The number of critics used in coming up with the          
                     Critic_score
•	User_Score	-  Score by Metacritic's subscribers
•	User_Count	-  Number of users who gave the user_score
•	Developer   -  Party responsible for creating the game
•	Rating 	-  The ESRB ratings

Rough Breakdown of Tasks: 

There are 16,598 records. The following are the pre-requiste:
1.	Python
2.	Jupyter Notebook
3.	Pandas (for data analysis)
4.	Matplotlib (for visualization)


We can do different types of analysis, in this the main goal was to analyze the sales of video games in different regions. The regions are North America, Europe, Japan, other countries(combined) and then the global sales (total of all the regions). The main idea was to visualize the sales for different genres, publishers and platforms. This would give the basic idea about the most popular genres, publishers and platforms amongst all. Also analyzing the effect of genres on sales in different region.

Few Activities/Steps but not limited that we are going to do are as follow:
A.	Dataset transformation: Such as replacing the null, NA etc.
B.	Dataset Load:  to Data frames  
C.	Data Analysis/Record Observation for the objective such as 
a.	Distribution of games with respect to consoles
b.	Distribution of games with respect to genres
c.	Distribution of games with respect to publishers
d.	For a genre of games, what variable helps make the most sales?
e.	What are the rankings of game genres within a certain nation?
f.	In the past five years, what genre of games has been gaining more popularity?
g.	What game has the highest sales in the world and what are its sales within multiple nations?
h.	1000 best-selling games for each region 
i.	Titles which are available for more than one platform
j.	Top contending platform
k.	Which type of platform is popular?
l.	Top selling genres
m.	Top publishers by Global Sales
n.	Number of Titles released by year
o.	Comparison Reg. Games sales by genre

D.	Data Visualization: Publish/Generate Reports	
