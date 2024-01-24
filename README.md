In this data set, you will find the raw user activity data from Dilan's blog between 1 January 2018 and 31 March 2018. It's a log with ~600.000 rows. The format is similar to what you had at Send-A-Tree but there are important differences.


The whole data log is one big file. You don't have to worry about automation and refreshing the data.
This is the .csv file. The field separator is a semi-colon (;).
The first column is the date and the time of the event, in this format: YYYY-MM-DD HH:MM:SS (eg. 2018-03-30 23:48:48).
The second column is the event type. There are three different event types:
read
subscribe
buy
The rest of the columns depend on the event type:
For read there are two options:
If this is the first visit from the given user, then the next fields are: country; user_id; source; topic
If it's a returning reader, then these are the fields: country; user_id; topic
For subscribe there is only one additional column: user_id
For buy there are two more columns: user_id and the price of the product the user bought.
Examples for each event types:
First time reader: 2018-03-30 23:59:56;read;country_5;2458361283;Reddit;Asia
Returning reader: 2018-03-31 05:04:50;read;country_4;2458361208;Africa
Subscriber: 2018-03-30 23:48:48;subscribe;2458173588
Purchase: 2018-03-30 23:11:30;buy;2458339835;80
Find out more by downloading and exploring the data set by yourself.
The country column has 8 different values:
country_1
country_2
country_3
...
country_8
The source column has 3 different values:
Reddit
AdWords
SEO
The topic column:
Africa
Europe
South America
North America
Australia
Asia
The course price column:
8
80
