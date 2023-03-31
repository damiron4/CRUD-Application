# CRUD-Application

This a CRUD application project created as a Database for different kind of diseases. 

Here is the report for each file


I used postgresql in order to create tables that were given in the instructions of the assignemnt. I also used some extensions from Visual Studio Code in order to make the process more faster. When I made insertions into the tables I took lots of data of WHO official site with diseases. 

In part 2 I used sqlalchemy library in python in order to make a connection to the postgresql database. 
The create_engine function enabled me to make a connection. The “text” function let me write code in SQL format instead of the “sqlalchemy’s” format. After I set everything up I wrote all 11 queries and made an output to the console. In queries 6-8 I made updates in the tables so I made an output before and after the queries to make it easier to check.

Bonus Part:
For the bonus part of the assignment, I used streamlit service that helped me to do a decent design of the site. The back-end part was mostly done by using psycopg2 library. It’s an alternative for the sqlalchemy. I used it because the queries were made faster and it compatible with streamlit library as well. Also, I didn’t have to add addition functions in order to write queries in SQL format because psycopg2 already see it as a part of the code. The pandas library helped me to create dynamic tables that I can easily update.  In the video I described how I created CRUD functions. Lastly, for the deployment I used Supabase server to store my database and streamlit’s cloud where the site is deployed. 
