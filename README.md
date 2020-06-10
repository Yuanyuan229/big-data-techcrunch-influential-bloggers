# big-data-techcrunch-influential-bloggers

## Business Initiatives: 
Blogs have been the major communication channel for many internet users for years, and 
blogsphere has recently become one of the most favored services on the Web. Techcrunch is one 
of them. By identifying influential bloggers, we would like to bring potential commercial or 
advertising values for Techcrunch. To be specific, through identifying influential and productive 
bloggers, then match them into several categories, Techcrunch can place ads more precisely and 
obtain a higher conversation rate. Moreover, by exploring the relationship between writing styles 
and metrics that indicating influence, the website can encourage its writers to produce better 
content. 

## Data: 
URL: https://www.kaggle.com/lakritidis/identifying-influential-bloggers-techcrunch 
The data set consists of four files: author.csv includes records of the 107 bloggers together with 
MEIBI and MEIBIX, two popular blogger evaluation metrics calculated based on numbers 
associated with the blog post (length, comments, inlinks, outlinks, etc.); comments.csv: contains 
the 746561 comments which were submitted by the readers of the 19464 posts of Techcrunch; 
inlinks.csv: contains 193808 pages that contain links to the 19464 posts of Techcrunch; 
posts.csv: includes 19464 posts authored by 107 bloggers. 

## Methodology: 
There exist preliminary models proposed various solutions to identify influential bloggers and 
MEIBI and MEIBIX are two metrics but they do not take the text data into consideration. 
Therefore, we would do sentiment analysis for comments, and authors with higher positive 
comments are more influential. Also, some NLP techniques will be applied to analyze the 
writing styles of these influential bloggers so that to explore the relationship between the writing 
styles and MEIBI and MEIBIX. A regression model will be applied: MEIBI/ MEIBIX is the 
dependent variable, and variables related to writing styles will be the independent variables. 
