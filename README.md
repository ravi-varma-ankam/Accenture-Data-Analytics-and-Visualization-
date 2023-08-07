# Accenture-Data-Analytics-Virtual-Programme
## Project Background

Social Buzz is a rapidly growing platform that prioritizes content and user anonymity. With over 500 million active users and 100,000 daily posts, Social Buzz faces the challenge of managing and analyzing vast amounts of content. This project is aimed at providing insights into the different content categories on Social Buzz with a focus on the top 5 categories with the largest aggregate popularity.

## Methodology:

### Data cleaning & modeling

7 data sets were received in CSV format from Social Buzz by email. A data model was developed to identify the relevant datasets required to answer the business problem which is to figure out the top 5 categories with the largest popularity.

Since the popularity is quantified by the score given to each reaction type, only 3 data sets containing the relevant information pertaining to content, reaction, and reaction types were used for the analysis.

Data cleaning was predominantly conducted in Jupyter Notebook. This involved the following;


The cleaned dataset was merged to create a final table.

## Data Exploration:

The final table contains 8 columns; Content ID, Reaction Types, and Date. Month, Content-Type, Category, Sentiment & Score. All variables except the score are categorical. To calculate the popularity score, the score for each content was added using the Sumifs function and split by category

To further explore the content categories I sought to address the following question with a focus on the business problem.

* Aside from popularity score, what are the top categories by reaction type and sentiments?
* How many unique posts are in the dataset?
* How many unique categories are there?
* How many reactions are there to the most popular category?
* What was the month with the most posts?
* How many reaction types are there?
* What was the top content type?
  
Once I concluded on what I wanted to visualize, I uploaded the data set to PowerBI and proceeded to create my interactive dashboard. I started by drawing a sketch of my vision for the dashboard on a piece of paper, then I built the template in Microsoft Powerpoint. I further customized the template to fit the needs of my visualization. 

## Analysis and finding

### Top 5 categories by Popularity Score

This bar chart depicts the top 5 content categories by popularity score. It shows that Animal related posts had the highest score closely followed by Science, while Food had the least score among the top 5.

It is important to note that food is a common theme with “Healthy Eating” and “Food” content in the top 5 categories.

### Top 5 categories by Reaction Percentage

This pie chart reveals the top 5 content categories by reaction percentage. The chart shows the percentage of users’ different reactions to the top 5 content categories.

It follows a similar pattern as the abovementioned bar chart; however, with respect to reaction percentage, Technology related content ranked the lowest amongst the top 5.

### Top 5 categories by Sentiment

This clustered bar chart reveals the top 5 content categories by reaction percentage. Sentiments are either Positive, Negative, or Neutral.

Regarding positive sentiment, animal content emerged as the most popular category, while food content received the lowest ranking among the top 5. When it comes to neutral sentiment, science content garnered the highest ranking, whereas food and healthy eating received the lowest scores. In terms of negative sentiment, animal content remained the highest-ranking category, while food content received the lowest ranking among the top 5 categories.

### Top 5 categories by Content Type

The stacked bar chart illustrates the leading content categories based on the percentage of user reactions. From the chart, it is evident that Animal content predominantly consisted of photos, while science and food content primarily included videos. Healthy eating and technology content was predominantly in audio format.

In terms of GIF content, its presence across the top 5 categories was consistently low, except for technology-related content, where GIFs were more prevalent.

Thank you for making out time to read through it. I learned Data Analysis, Storytelling, Data Visualization, Data Understanding, Data Modelling Teamwork, Strategy Project Planning PowerBI, Pandas, Presentation, Communication and Public speaking
## Dashboard Example

![image](https://user-images.githubusercontent.com/86049878/226091077-28f21c42-ee82-4f83-b1f7-ba28f6b0b4e6.png)
