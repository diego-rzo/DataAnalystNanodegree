# Project 3: Wrangle and analyze data

During this project a database is built gathering data from different sources.
Then the data is assesses and finally cleaned to produce some insights and visualizations.

## Gathering
In order to get all the information necessary to build the database, the information was collected from three different sources.
The first one is a file with the tweeter information from the account WeRateDogs, the second one is a file coming from some automatic classification algorithms and the third one was actually the result of querying the tweeter API. In order to query the API of tweeter it was necessary to create an account for developers and get permissions to send some requests. After that using the python's library Tweepy the information of all the tweets was consulted using their ids.

## Assesing
After gathering the data it was assessed by visual inspection, and also programatically using some functions included in the pandas library. This assesing proccess gave as result some issues that are listed below. But it is important to notice that only some issues were documented and it doesn't represent the totallity of the necessary for completely wrangling the data.

## Cleaning
During the cleaning proccess, the found issues were not solved in the order they are presented, because sometimes while solving a tidyness problem some other quality issues disappeared. But in any case all of them where mentioned and solved. In general every problem is taken one by one, then a solution is proposed in the definition, after the code is written in order to solve the problem itself and finally the data is assessed to see if the code did what it was intended to do.

## Storing
Once the data is cleaned and ordered in one dataframe, it is stored in a file in format .csv which is supposed to be a clean and well wrangled dataframe. But as was already said, it is not exhaustive and it doesn't cover all the problems that the data can contain.

## Insights
After the data is wrangled it is possible to analyse it and produce some insights and visualisations. So with this purpose some variables were compared and it was found that the pupper dog type is the most common. And also the twitter rating of the dogs was compared with the tweeter measures like favorite counter and retweet counter finding a not very strong tendency but still some. It shows that when dogs were well rated by the owners who posted the tweets, it is more likely to find higher values of retweet counters and the same for the favorite counters. Which might mean that well rated dogs by their owners are more likely to be well appreciated by the social network community.
