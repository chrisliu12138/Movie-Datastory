# Movie-Datastory
Southampton Data Visualization Coursework-Tableau

# I.	DATA STORY SUMMARY  
Data story is a beautiful and engaging work of art. Completing a perfect and fascinating data story is something to be proud of, so please follow me into the movie data story. The topic is movie data analysis, including which types of movies are more popular from the last century to the present? How do movies based on novels perform compared to non-fiction movies? Who is the best director and so on. Data story interface is shown in Figure 1.1.

![image](https://user-images.githubusercontent.com/61305941/213340255-ada73a2a-bfa3-4752-bb96-6176884469d3.png)

Fig 1.1 Data story interface

The target audience of this data story is very wide, whether you are a person who loves movies and wants to understand the trend of movie genres, or a filmmaker who wants to analyse high-profit movie genres for movie giants, of course, just want to see which directors are more popular.

There are the use cases it supports:

Case 1: Choose one of today's hottest movie genres.

Through the data story of the movie, we can use the line graph to conclude that the movie genre changes with the times, and the probability that many people watch the genre today will be very low.

Case 2: A filmmaker or star chooses to make the most lucrative genre of film today.

By comparing the profit and income of different films of the two major companies, Paramount and Universal, it is possible to predict the types of films that will make money.

Case 3: Will the film adaptation of the novel destroy the original or sublimate the original?

By looking at the number of movies adapted from novels, one can deduce whether most people like adaptations.

Case 4: One wonders who is the best director?

One can find out who is the tallest relative to popularity. And comprehensive comparison of profits, popularity and ratings, who is the best overall.
I use patterns for engagement as the overall narrative pattern[1]. As we know, one way to provoke engagement can be through emotion. Another way is to start with a rhetorical question. By directly addressing the audience, a rhetorical question can connect the narrator with the audience, and can trigger its will to answer that question, even if only for a moment. In this sense, a rhetorical question can set the context for a subsequent exploration of the reasons behind the answer, which the narration can then reveal and explain[2]. Examples for rhetorical questions in data-driven stories are also widespread. 

![image](https://user-images.githubusercontent.com/61305941/213340346-b27683e3-df2e-4521-9103-f026602525bc.png)

Fig 1.2 Two contrast videos

As shown in Figure 1.2. First of all, my movie story starts with two videos, which let the audience watch two pieces of film works with different styles without any prediction. Next, I will ask the audience to think about what they think about the film, and finally introduce the subject of film data slowly. This can well stimulate the audience's will and make the whole data story more vivid.
# II.	DATASET SUMMARY  
There are four documents of my dataset, all of which are .csv files found from the Kaggle website.

![image](https://user-images.githubusercontent.com/61305941/213340366-5bf75d2f-87f4-4ca2-bb8c-c01a67bce223.png)

Fig 2.1 Dataset names

![image](https://user-images.githubusercontent.com/61305941/213340392-065b1057-a3ab-4813-866f-3b109038ea50.png)
 
Fig 2.2 Dataset details

As shown in Figure 2.1 and 2.2, including one large data with more than 20000 lines and three with more than 10000 lines.

![image](https://user-images.githubusercontent.com/61305941/213340408-f0d4f216-b4d7-4717-b430-7e0367a869b2.png)

Fig 2.3 Dataset details in tableau

As shown in Figure 2.3. What I need to do is manually import all data sets in the data source of tableau, set the field information, and match the migrated data with the field information to start the data visualization drawing creation. The next thing to do is set to extract connection not live connection to ensure that the visual image can be exported to the web page. The variables used are as follows: release_year, genre, budget, revenue, original_title, production company, popularity and vote_average.
# III.	VISUALISATIONS  
## A.	(Film genres) Visualisation 1

1)	Description

![image](https://user-images.githubusercontent.com/61305941/213340741-dae36c8c-0a0e-425f-96fe-dc408e0c800f.png)

Fig 3.1 Film genres visualisation

The effect of the first data visualization is shown in Figure 3.1. The number ranking of different styles of films and the change over time from 1960 to 2015 are shown by using histogram and line graph. The line graph uses different colours to represent key features that different types of films, which is more convenient for readers to read and compare.

Finally, the conclusion is as follows:

a. From 1960 to 2015, the top five films produced were Drama, Comedy, Thriller, Action and Romance.

b. Drama and action are the two types with the largest number for a long time. Before 2003, the number was almost the same, and the number of drama films was slightly higher. After 2003, the number of drama films began to widen the gap with the second place action films.

c. From the perspective of various style trends, the plot category has been in a state of rapid growth, comedy has entered a high-speed growth since 1976, documentary. The number of horror films and thrillers has increased sharply since 2004.

The interaction is that when the mouse hovers over each histogram and line chart, specific numbers will be displayed. The small button next to the genre count sorts the histogram. The time interval of release_year can be adjusted arbitrarily, such as 1960-1965. 

2)	Justification
Bar charts are very effective at comparing other aspects of a single degree, and are the most common type of data variable. A graph connects multiple disparate data points and presents them as a continuously changing whole. This method simply and directly presents the change of one value relative to another. So these two graphs are very effective for representing changes in movie genres over time.

3)	Narrative Design Patterns
This film genres visualisation use patterns for engagement. First of all, the two line charts with a lot of lines and colours quickly attract your attention, and then the attention returns to the chart itself. This will make the story more readable and interesting.

4)	Strengths and Weaknesses
Because there are too many years on the abscissa, in order to see the change information more quickly, I gave up using the dynamic histogram and line chart, making the change process weaker than the dynamic chart.

5)	Improvements
The direction of improvement is mainly to increase the numerical labeling of the highest point and the lowest point, which will be more intuitive. And can also add visualizations in recent years separately, because data decades ago may not be meaningful. 

## B.	(Paramount and Universal) Visualisation 2

1)	Description

![image](https://user-images.githubusercontent.com/61305941/213340811-4614615f-a3a0-4865-93d0-d96edc662a8a.png)

Fig 3.2 Paramount and Universal visualisation

Figure 3.2 shows the difference between the previous data indicators of Universal and Paramount.

Finally, the conclusion is as follows:

a. In general, from 1960 to 2015, Universal Pictures was slightly higher than Paramount Pictures in terms of production volume, budget, revenue and so on.

b. From the perspective of time, before the 1990s, the data indicators of the two companies were not comparable. From the middle and late 1990s to 2011, Universal Pictures began to significantly exceed Paramount's budget. In addition, the income and influence of Paramount also exceeded that of Paramount during this period. From 2011 to 2015, Paramount began to catch up with the budget, and the data of the two companies entered a sticky state again.

c. Among the films with the highest income of the two companies, the film with the highest income of Paramount is Titanic, and the film with the highest income of Universal Pictures is Furious 7. Overall, the film with the highest income of Universal Pictures is slightly more than Paramount.

Similarly, we hover over the mouse to interact and display specific numbers. The small button next to profit sorts the histogram.

2)	Justification
Due to the comparison of the two companies, it is the finishing touch and the magic point to use two different colours for the column chart and the line chart.

3)	Narrative Design Patterns
This visualisation part used patterns for argumentation. Through changes of a single graphic over time[1]. Comparison allows the narrator to make the point about equality of both data sets, to explicitly highlight differences and similarities, or to give reasons for their difference[2].

4)	Strengths and Weaknesses
The area of the histogram on the left is small, and the area of the line chart with earlier years has a small change range and occupies a large area of the page.

5)	Improvements
Slightly expand the size of the coordinate visualization bar graph on the left, and increase the function that the time from 1960 to 2015 in the first genre data can be adjusted and displayed at will.

## C.	(Film performance based on novel adaptation) Visualisation 3

1)	Description

![image](https://user-images.githubusercontent.com/61305941/213340878-554b0e04-a9bd-47b6-86c3-4cd7a15b3a10.png)

Fig 3.3 Film performance based on novel adaptation visualisation

This visualization shows how the film based on novel adaptation performs compared with the film based on non-fiction adaptation? Whether movies adapted from novels are more popular.

Finally, the conclusion is as follows:

a. In terms of budget, income, and popularity, movies based on novels are much higher than other non-adapted films.

b. Movies based on novel adaptation peaked respectively in 1994 and 2003, and the budget investment for novel adaptation films has also increased year by year since 1994.

The mouse hover can interact with the visual chart, showing the specific average and year. Similarly, you can also click on a column in a single histogram, so that the line chart will only display the selected Film performance.

2)	Justification

Our question is, are movies based on novels more popular? How do fiction films perform compared to non-fiction films? Therefore, it involves comparison based on novel and others, and calculates the average value of budget. Two large line charts are selected to highlight the relationship between based on novel and others. At the same time, a small histogram is placed on the left to make the data display more rigorous.

3)	Narrative Design Patterns

This visualisation used engagement as narrative design patterns. As can be seen as the feeling of being part of the story, of being connected to it, and being in control over the interactions with the story’s content[3].

4)	Strengths and Weaknesses

When viewing this page, it is easy to focus on the large line graph on the right and ignore the comparison of the budgets, profits and revenues of the two companies on the left.

5)	Improvements

Increase the area of the comparison bar graph to make it easier for people to see, but don't exceed the size on the right.

## D.	(Best director) Visualisation 4

1)	Description
 
![image](https://user-images.githubusercontent.com/61305941/213340936-26a2778d-6489-42d9-a505-3eff135c4849.png)

Fig 3.4 Best director visualisation

As shown in Figure 3.3, these three histograms in this visualization respectively reflect the highest total profit ranking of directed movies, the director popularity ranking and the movie profit ranking directed by Steven Spielberg. The final scatter plot reflects the director's comprehensive data distribution.

Finally, the conclusion is as follows:

a. The most profitable director is Steven Spielberg, and his two films, Jaws and ET, contributed 27.85% of all profits to him.

b. Compared with popularity, the highest is Christopher Nolan.

c. By comprehensive comparison of profit, popularity and score, Steven Spielberg has high data, which can be said to be the most successful director.

Click the small arrow button to sort the visualization graph is allowed. Click a column so that the line chart will only display the selected Director data.

2)	Justification

The problem to be solved in this visualization is who is the best director, and various data focus on experiencing the maximum value, so it is most appropriate to use sortable bar charts.

3)	Narrative Design Patterns

Patterns for Engagement is the main narrative sequence of the Best director visualization. One example for this pattern is the NY Times’ story on education; the viewer is asked to draw a line inside a graph, representing the distribution between household income and percentage of children with a college degree. Make-a-guess questions can stimulate the audiences’ curiosity to know the answer, and can engage them in causal reasoning about the phenomenon, while providing a motivation for following the narrative. On the one hand, audiences are asked to question their own perception of reality, and on the other hand, they are asked to question why this perception may have been wrong—in the case of a mismatch between their perception of reality and the actual data. Eventually, the narrative can also reveal what other audiences have guessed (a device used in the example of the college degrees, as well).

4)	Strengths and Weaknesses
The colour of the visualization chart is too single, all blue, which may cause aesthetic fatigue and even cause the audience to be unwilling to read the information in the table. There are too many histograms on this page, which are not as vivid as other dynamic tables.

5)	Improvements
Merge several histograms into one graph, different colours or shapes can represent different data. Add a variety of histogram colours, or change it to a dynamic graph, which will make readers more curious and therefore pay attention to the roundness.

## E.	(Director story) Visualisation 5

1)	Description

![image](https://user-images.githubusercontent.com/61305941/213341072-6833b2e6-79a3-477f-8ac3-cb2533e132f6.png)

Fig 3.5 Director story visualisation

Figure 3.5 puts the previous data visualization director information together with labels, and adds the analysis information of the labels, which is more readable and concise than the previous ones.

The director’s data visualization has added labels. You can click on different labels to view the text content on the top, and the visualization below will also change accordingly.

2)	Justification
Labels can be used to grab the reader's attention first, and the reader will not see a large number of tables in an instant, which is friendly and interactive.

3)	Narrative Design Patterns
This directory story used patterns for argumentation. Because the visual information about the director is integrated in a label, what we see at first glance must be the conclusion in the label. After we understand it, we can study the histogram and scatter chart of visualization in turn.

4)	Strengths and Weaknesses
The defect of the director's information visualization image is that the table is a circle smaller than other visualized images, and it is not aligned in the web page. At the same time, the only difference between this visualization and the previous graphic is that there is a label with conclusions.

5)	Improvements
It is very simple to improve and modify this module. We need to modify the size of the visual interface so that there will be no black edges on the right side of the page. Or, add a summary of this visualization in the small space.

# IV.	SUMMARY

[1] Bach, Benjamin, et al. "Narrative design patterns for data-driven storytelling." Data-driven storytelling. AK Peters/CRC Press, 2018. 107-133.

[2] B. Bach, N. Riche, S. Carpendale and H. Pfister, "The Emerging Genre of Data Comics" in IEEE Computer Graphics and Applications, vol. 37, no. 03, pp. 6-13, 2017.

[3] "2021 VGTC Visualization Significant New Researcher Award—Michelle Borkin, Northeastern University and Benjamin Bach, University of Edinburgh" in IEEE Transactions on Visualization & Computer Graphics, vol. 28, no. 01, pp. xxvii-xxviii, 2022. 
