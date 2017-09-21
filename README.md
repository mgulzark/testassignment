# Assignment Results

<h3>Framework(Codeignitor)</h3>

I use Codeignitor as a framework to make this assignment. Basically I work with Codeignitor, Yii, Laravel and unfortunately not with Symphony.
This assignment is important for me so i use the framework for which i am much experienced. However It takes me 4 to 5 days to be familier with Symphony and then i can use that also. 

# Tasks
<h3>1. Specify a default controller</h3>
Before you start you need to create a dummy database only and no tables.
After setting the application at your server, access the base url and you will see these results.

<h3>2. Use the api.nasa.gov</h3>
Yes i used this API and it fetch records for last 3 days.

<h3>3. Write a command</h3>
All points under this section are done. please asccess the url (http://base_url/neo) and you will see the results. 
It will create the table and insert all asteriod records into the database and also show you total count of asteriods.

<h3>4. Create a route /neo/hazardous </h3>
yes please now access the same url and it will return the hazardous asteroid records.

<h3>5. Create a route /neo/fastest?hazardous=(true|false)</h3>
Yes please acess the url as listed, and it will show 2 fastest asteriod record based on query parameter "hazardous" and by default hazardous = false.


<h3>6. Create a route /neo/best-year?hazardous=(true|false)</h3>
I have done this, but i guess we have a small problem here, i am fetching records for last 3 days, so it will be the same month and same year. 
I guess it needs to be named as "Best Day". I have done this and it shows day with most asteriod based on query parameter "hazardous".

<h3>7. Create a route /neo/best-month?hazardous=(true|false)</h3>
I have not done this, becasue As stated above for last 3 days, it will be the same month. 
