# SELECT Statement Exercises (PostgreSQL)

### Exercise 1 
Find the model number, speed and hard drive capacity for all the PCs with prices below $500.  

<br>

### Exercise 2 
List all printer manufacturers.  
<br>



### Exercise 3 
Find the model number, RAM and screen size of the laptops with prices over $1000.  

<br>


### Exercise 4 
Find all records from the Printer table containing data about color printers.  

<br>


### Exercise 5 
Find the model number, speed and hard drive capacity of PCs cheaper than $600 having a 12x or a 24x CD drive.  

<br>


### Exercise 6 
For each manufacturer producing laptops with a hard drive capacity of 10 Gb or higher, find the speed of such laptops.  

<br>


### Exercise 7 
Get the models and prices for all commercially available products (of any type) produced by maker B.  

<br>


### Exercise 8 
Find the manufacturers producing PCs but not laptops.  

<br>


### Exercise 9 
Find the manufacturers of PCs with a processor speed of 450 MHz or more.  



<br>

### Exercise 10 
Find the printer models having the highest price. Result set: model, price.  


<br>

### Exercise 11 
Find out the average speed of PCs.  


<br>

### Exercise 12 
Find out the average speed of the laptops priced over $1000.  


<br>

### Exercise 13 
Find out the average speed of the PCs produced by maker A.  


<br>

### Exercise 14 
For the ships in the Ships table that have at least 10 guns, get the class, name, and country.  
<br>



### Exercise 15 
Get hard drive capacities that are identical for two or more PCs.  
<br>



### Exercise 16 
Get pairs of PC models with identical speeds and the same RAM capacity.  
Each resulting pair should be displayed only once, i.e. (i, j) but not (j, i).  
Result set: model with the bigger number, model with the smaller number, speed, and RAM.    

<br>


### Exercise 17 
Get the laptop models that have a speed smaller than the speed of any PC.  
Result set: type, model, speed.  

<br>


### Exercise 18 
Find the manufacturers of the cheapest color printers.  
Result set: maker, price.  


<br>

### Exercise 19 
For each manufacturer having models in the Laptop table, find out the average screen size of the laptops.  


<br>

### Exercise 20 
Find the manufacturers producing at least three distinct models of PCs.  
Result set: maker, number of PC models.  


<br>

### Exercise 21 
Find out the maximum PC price for each manufacturer having models in the PC table.  


<br>

### Exercise 22 
For each value of PC speed that exceeds 600 MHz, find out the average price of PCs with identical speeds.  
<br>



### Exercise 23 
Get the manufacturers producing both PCs having a speed of 750 MHz or higher and laptops with a speed of 750 MHz or higher.  
<br>



### Exercise 24 
List the models of any type having the highest price of all products present in the database.  
<br>



### Exercise 25 
Find the printer manufacturers also producing PCs with the lowest RAM capacity and the highest processor speed of all PCs having the lowest RAM capacity.  
<br>



### Exercise 26 
Find out the average price of PCs and laptops produced by manufacturer A.  
<br>



### Exercise 27 
Find out the average hard disk drive capacity of PCs produced by manufacturers who also manufacture printers.  

<br>


### Exercise 28 
Using Product table, find out the number of manufacturers who produce only one model.  
<br>



### Exercise 29 
Under the assumption that receipts of money (inc) and payouts (out) are registered not more than once a day for each collection point 
[i.e. the primary key consists of (point, date)], write a query displaying cash flow data (point, date, income, expense).  

<br>


### Exercise 30 
Under the assumption that receipts of money (inc) and payouts (out) can be registered any number of times a day for each collection point 
[i.e. the code column is the primary key], display a table with one corresponding row for each operating date of each collection point.  

<br>


### Exercise 31 
For ship classes with a gun caliber of 16 in. or more, display the class and the country.  

<br>


### Exercise 32 
One of the characteristics of a ship is one-half the cube of the calibre of its main guns (mw).  
Determine the average ship mw with an accuracy of two decimal places for each country having ships in the database.  
<br>



### Exercise 33 
Get the ships sunk in the North Atlantic battle.  

<br>


### Exercise 34 
In accordance with the Washington Naval Treaty concluded in the beginning of 1922, it was prohibited to build battle ships with a displacement of more than 35 thousand tons.  
Get the ships violating this treaty (only consider ships for which the year of launch is known).  

<br>


### Exercise 35 
Find models in the Product table consisting either of digits only or Latin letters (A-Z, case insensitive) only.  
Result set: model, type.  

<br>


### Exercise 36 
List the names of lead ships in the database (including the Outcomes table).  

<br>


### Exercise 37 
Find classes for which only one ship exists in the database (including the Outcomes table).  

<br>


### Exercise 38 
Find countries that ever had classes of both battleships (‘bb’) and cruisers (‘bc’).  

<br>


### Exercise 39 
Find the ships that 'survived for future battles'; that is, after being damaged in a battle, they participated in another one, which occurred later.  

<br>


### Exercise 40 
Get the manufacturers who produce only one product type and more than one model. Output: maker, type.  

<br>


### Exercise 41 
For each manufacturer who has models at least in one of the tables PC, Laptop, or Printer, determine the maximum price for products.  
Output: maker; if there are NULL values among the prices for the products of a given manufacturer, display NULL for this maker, otherwise, the maximum price.  

<br>


### Exercise 42 
Find the names of ships sunk at battles, along with the names of the corresponding battles.  

<br>


### Exercise 43 
Get the battles that occurred in years when no ships were launched into water.  


<br>

### Exercise 44 
Find all ship names beginning with the letter R.  

<br>


### Exercise 45 
Find all ship names consisting of three or more words (e.g., King George V).  

<br>


### Exercise 46 
For each ship that participated in the Battle of Guadalcanal, get its name, displacement, and the number of guns.  

<br>


### Exercise 47 
Find the countries that have lost all their ships in battles.  

<br>


### Exercise 48 
Find the ship classes having at least one ship sunk in battles.  

<br>


### Exercise 49 
Find the names of the ships having a gun caliber of 16 inches (including ships in the Outcomes table).  

<br>


### Exercise 50 
Find the battles in which Kongo-class ships from the Ships table were engaged.  

<br>


### Exercise 51 
Find the names of the ships with the largest number of guns among all ships having the same displacement (including ships in the Outcomes table).  

<br>


### Exercise 52 
Determine the names of all ships in the Ships table that can be a Japanese battleship having at least nine main guns 
with a caliber of less than 19 inches and a displacement of not more than 65 000 tons.  

<br>


### Exercise 53 
With a precision of two decimal places, determine the average number of guns for the battleship classes.  

<br>


### Exercise 54 
With a precision of two decimal places, determine the average number of guns for all battleships (including the ones in the Outcomes table).  

<br>


### Exercise 55 
For each class, determine the year the first ship of this class was launched.  
If the lead ship’s year of launch is not known, get the minimum year of launch for the ships of this class.  
<br>



### Exercise 56 
For each class, find out the number of ships of this class that were sunk in battles.  

<br>


### Exercise 57 
For classes having irreparable combat losses and at least three ships in the database, display the name of the class and the number of ships sunk.  

<br>


### Exercise 58 
For each product type and maker in the Product table, find out, with a precision of two decimal places, 
the percentage ratio of the number of models of the actual type produced by the actual maker to the total number of models by this maker.  

<br>


### Exercise 59 
Calculate the cash balance of each buy-back center for the database with money transactions being recorded not more than once a day.  

<br>


### Exercise 60 
For the database with money transactions being recorded not more than once a day, calculate the cash balance of each buy-back center at the beginning of 4/15/2001.  
Note: exclude centers not having any records before the specified date.  

<br>


### Exercise 61 
For the database with money transactions being recorded not more than once a day, calculate the total cash balance of all buy-back centers.  


<br>

### Exercise 62 
For the database with money transactions being recorded not more than once a day, calculate the total cash balance of all buy-back centers at the beginning of 04/15/2001.  


<br>

### Exercise 63 
Find the names of different passengers that ever travelled more than once occupying seats with the same number.  

<br>


### Exercise 64 
Using the Income and Outcome tables, determine for each buy-back center the days when it received funds but made no payments, and vice versa.  

<br>


### Exercise 65 
Number the unique pairs {maker, type} in the Product table, ordering them as follows:  
\- maker name in ascending order;  
\- type of product (type) in the order PC, Laptop, Printer.  
If a manufacturer produces more than one type of product, its name should be displayed in the first row only;
other rows for THIS manufacturer should contain an empty string (').  

<br>


### Exercise 66 
For all days between 2003-04-01 and 2003-04-07 find the number of trips from Rostov.  


<br>

### Exercise 67 
Find out the number of routes with the highest number of flights.  
A - B and B - A are considered to be DIFFERENT routes.  
Use the Trip table only.  

<br>


### Exercise 68 
Find out the number of routes with the highest number of flights.  
A - B and B - A are to be considered the SAME route.  
Use the Trip table only.  
<br>



### Exercise 69 
Using the Income and Outcome tables, find out the balance for each buy-back center by the end of each day when funds were received or payments were made.  
Note that the cash isn’t withdrawn, and the unspent balance/debt is carried forward to the next day.  

<br>


### Exercise 70 
Get the battles in which at least three ships from the same country took part.  


<br>

### Exercise 71 
Find the PC makers with all personal computer models produced by them being present in the PC table.  


<br>

### Exercise 72 
Among the customers using a single airline, find distinct passengers who have flown most frequently.  

<br>


### Exercise 73 
For each country, determine the battles in which the ships of this country did not participate.  
<br>



### Exercise 74 
Get all ship classes of Russia. If there are no Russian ship classes in the database, display classes of all countries present in the DB.  

<br>


### Exercise 75 
For makers who have products with a known price in at least one of the Laptop, PC, or Printer tables, find the maximum price for each product type.  

<br>


### Exercise 76 
Find the overall flight duration for passengers who never occupied the same seat.  

<br>


### Exercise 77 
Find the days with the maximum number of flights departed from Rostov.  


<br>

### Exercise 78 
For each battle, get the first and the last day of the month when the battle occurred.  

<br>


### Exercise 79 
Get the passengers who, compared to others, spent most time flying.  

<br>


### Exercise 80 
Find the computer hardware makers not producing any PC models absent in the PC table.  

<br>


### Exercise 81 
For each month-year combination with the maximum sum of payments (out), retrieve all records from the Outcome table.  


<br>

### Exercise 82 
Assuming the PC table is sorted by code in ascending order, find the average price for each group of six consecutive personal computers.  


<br>

### Exercise 83 
Find out the names of the ships in the Ships table that meet at least four criteria from the following list:  
numGuns = 8,  
bore = 15,  
displacement = 32000,  
type = bb,  
launched = 1915,  
class = Kongo,  
country = USA.  
<br>



### Exercise 84 
For each airline, calculate the number of passengers carried in April 2003 (if any) by ten-day periods.   
Consider only flights that departed that month.  

<br>


### Exercise 85 
Get makers producing either printers only or personal computers only; in case of PC manufacturers they should produce at least 3 models.  

<br>


### Exercise 86 
For each maker, list the types of products in alphabetic order, using a slash ("/") as a delimiter.  

<br>


### Exercise 87 
Supposing a passenger lives in the town his first flight departs from, find non-Muscovites who have visited Moscow more than once.  

<br>


### Exercise 88 
Among those flying with a single airline find the names of different passengers who have flown most often.  
<br>



### Exercise 89 
Get makers having most models in the Product table, as well as those having least.  

<br>


### Exercise 90 
Display all records from the Product table except for three rows with the smallest model numbers and three ones with the greatest model numbers.  


<br>

### Exercise 91 
Determine the average quantity of paint per square with an accuracy of two decimal places.  
<br>



### Exercise 92 
Get all white squares that have been painted only with spray cans empty at present.  


<br>

### Exercise 93 
For each airline that transported passengers calculate the total flight duration of its planes.  


<br>

### Exercise 94 
For seven successive days starting with the earliest date when the number of departures from Rostov was maximal, get the number of flights departed from Rostov.  

<br>


### Exercise 95 
Using the Pass_in_Trip table, calculate for each airline:  
\- the number of performed flights;  
\- the number of plane types used;  
\- the number of different passengers that have been transported;  
\- the total number of passengers that have been transported by the company.  
<br>



### Exercise 96 
Considering only red spray cans used more than once, get those that painted squares currently having a non-zero blue component.  
<br>



### Exercise 97 
From the Laptop table, select rows fulfilling the following condition:  
the values of the speed, ram, price, and screen columns can be arranged in such a way that each successive value exceeds two or more times the previous one.  
Note: all known laptop characteristics are greater than zero.  

<br>


### Exercise 98 
Display the list of PCs, for each of which the result of the bitwise OR operation performed on the binary representations 
of its respective processor speed and RAM capacity contains a sequence of at least four consecutive bits set to 1.  

<br>


### Exercise 99 
Only Income_o and Outcome_o tables are considered. It is known that no money transactions are performed on Sundays.  
For each buy-back center (point) and each funds receipt date, determine the encashment date according to the following rules:  
\- The encashment date is the same as the receipt date if there is no payment entry in the Outcome_o table for this date and point  
\- Otherwise, the first possible date after the receipt date is used that doesn’t fall on Sunday and doesn’t have a corresponding payment entry in the Outcome_o table for the point in question.  

<br>


### Exercise 100 
Write a query that displays all operations from the Income and Outcome tables as follows:  
date, sequential record number for this date, buy-back center receiving funds, funds received, buy-back center making a payment, payment amount.  
All revenue transactions for all centers made during a single day are ordered by the code field, and so are all expense transactions.  
If the numbers of revenue and expense transactions are different for a day, display NULL in the corresponding columns for missing operations.  

<br>


### Exercise 101 
The Printer table is sorted by the code field in ascending order.  
The ordered rows form groups: the first group starts with the first row, each row having color=’n’ begins a new group, the groups of rows don’t overlap.  
For each group, determine the maximum value of the model field (max_model), the number of unique printer types (distinct_types_cou), and the average price (avg_price).  
For all table rows, display code, model, color, type, price, max_model, distinct_types_cou, avg_price.  


<br>

### Exercise 102 
Find the names of different passengers who travelled between two towns only (one way or back and forth).  


<br>

### Exercise 103 
Find out the three smallest and three greatest trip numbers. Output them in a single row with six columns, ordered from the least trip number to the greatest one.  
Note: it is assumed the Trip table contains 6 or more rows.  
<br>



### Exercise 104 
For each cruiser class whose quantity of guns is known, number its guns sequentially beginning with 1.  

<br>


### Exercise 105 
Statisticians Alice, Betty, Carol and Diana are numbering rows in the Product table.  
Initially, all of them have sorted the table rows in ascending order by the names of the makers.  
Alice assigns a new number to each row, sorting the rows belonging to the same maker by model in ascending order.  
The other three statisticians assign identical numbers to all rows having the same maker.  
Betty assigns the numbers starting with one, increasing the number by 1 for each next maker.  
Carol gives a maker the same number the row with this maker's first model receives from Alice.  
Diana assigns a maker the same number the row with this maker's last model receives from Alice.  
Output: maker, model, row numbers assigned by Alice, Betty, Carol, and Diana respectively.  

<br>


### Exercise 106 
Let v1, v2, v3, v4, ... be a sequence of real numbers corresponding to paint amounts b_vol, sorted by b_datetime, b_q_id, and b_v_id in ascending order.  
Find the transformed sequence P1=v1, P2=v1/v2, P3=v1/v2*v3, P4=v1/v2*v3/v4, ..., where each subsequent member is obtained from the preceding one by either multiplication by vi (for an odd i) or division by vi (for an even i).  
Output the result as b_datetime, b_q_id, b_v_id, b_vol, Pi, with Pi being the member of the sequence corresponding to the record number i. Display Pi with eight decimal places.  

<br>


### Exercise 107 
Find the company, trip number, and trip date for the fifth passenger from among those who have departed from Rostov in April 2003.  
Note. For this exercise it is assumed two flights can’t depart from Rostov simultaneously.  


<br>

### Exercise 108 
The restoration of the exhibits of the Triangles department of the PFAS museum has been carried out according to the performance specification.   
For each record in the utb table, the painters restored the paint on the side of every geometric figure, provided this side had a length equal to b_vol.  
Get all triangles having the paint on all their sides restored, except for equilateral, isosceles, and obtuse ones.  
For each triangle (yet without duplicates), display three values X, Y, Z, where X is the length of the short, Y – of the medium, and Z – of the long triangle side.  


<br>

### Exercise 109 
Display:  
\- The names of all squares that are black or white.  
\- The total number of white squares.  
\- The total number of black squares.    


<br>

### Exercise 110 
Find out the names of different passengers who ever travelled on a flight that took off on Saturday and landed on Sunday.  

<br>


### Exercise 111 
Get the squares that are NEITHER white NOR black, and painted with different colors in a 1:1:1 ratio.  

<br>


### Exercise 112 
What maximal number of black squares could be colored white using the remaining paint?  

<br>


### Exercise 113 
How much paint of each color is needed to dye all squares white?  

<br>


### Exercise 114 
Find the names of different passengers who occupied the same seat most often.  
<br>



### Exercise 115 
Let’s consider isosceles trapezoids, each of them having an inscribed circle tangent to all four sides.  
Besides, each side has an integer length belonging to the set of b_vol values.  
Output the result in 4 columns named Up, Down, Side, Rad, where Up is the shorter base, Down - the longer base, Side is the length of the legs, and Rad - the radius of the inscribed circle (with 2 decimal places).  


<br>

### Exercise 116 
Assuming a painting event lasts exactly one second determine all continuous time intervals in the utB table that are more than one second long.  
Output: date of the painting event that starts the respective interval, date of the painting event that ends it.  

<br>


### Exercise 117 
For each country in the Classes table, determine the maximal value among the following three expressions:  
numguns\*5000, bore\*3000, displacement.  
The result set consists of 3 columns:  
\- country;  
\- maximal value;  
\- the word "numguns" if numguns\*5000 is the maximum, "bore" if it’s bore\*3000, or "displacement" if it’s the displacement.  
Note. If the maximum occurs for more than one expression, display them all in a separate row each.  
<br>



### Exercise 118 
The PFAS Museum Director elections are held in leap years only, on the first Tuesday after the first Monday in April.  
For each date from the Battles table, determine the closest election date following it.  
Output: battle name, date of battle, election date. Note: output format for dates should be "yyyy-mm-dd".  

<br>


### Exercise 119 
Group all paintings by days, months and years separately. The group identifiers should be "yyyy" for years, "yyyy-mm" for months and "yyyy-mm-dd" for days.  
Displayed should be only groups with more than 10 distinct moments of time (b_datetime) at which paintings have occurred.  
Result set: group identifier, total quantity of paint used within a group.  


<br>

### Exercise 120 
For each airline that has transported at least one passenger, calculate the arithmetic, geometric, quadratic and harmonic means of its respective planes’ flight durations (in minutes) with an accuracy of two decimal places.  
In addition, output the aforementioned characteristics for all flights in a separate line, using the word ‘TOTAL’ as the airline name.  
Result set: company name, arithmetic mean {(x1 + x2 + … + xN)/N}, geometric mean {(x1 * x2 * … * xN)^(1/N)}, quadratic mean { sqrt((x1^2 + x2^2 + ... + xN^2)/N)}, harmonic mean {N/(1/x1 + 1/x2 + ... + 1/xN)}.  


<br>

### Exercise 121 
Get the names of all ships in the database that definitely were launched before 1941.  


<br>

### Exercise 122 
Assuming the first town a passenger departs from is his/her residence, find out the passengers who are away from home.  

<br>


### Exercise 123 
For each maker find out the number of available products (of any type) with a non-unique price and the number of such non-unique prices.  

<br>


### Exercise 124 
Among the passengers who flew with at least two airlines find those who traveled the same number of times with each of these airlines.  
Display the names of such passengers.  

<br>


### Exercise 125 
Put all data about models on sale and their prices (from the tables Laptop, PC and Printer) into a single table named LPP, and enumerate its records (by assigning an id to each row) without gaps or duplicates.  
Assume the models in each of the original three tables to be sorted in ascending order by the code field.  
The unified LPP table numbering has to be set up according to the following rule: first go the first models from the tables (Laptop, PC, and Printer), then the last models, after that - the second models in the original tables, then, the penultimate ones, etc.  
In case there are no models of a particular type left, number the remaining models of other types only.  
Output the LPP table in 4 columns: id, type, model, and price. The type field contains one of the strings 'Laptop', 'PC', or 'Printer'.  


<br>

### Exercise 126 
For the sequence of passengers ordered by id_psg find out the ones having the maximum number of flight bookings, as well as the ones directly preceding and following them in the sequence.  
The first passenger in the sequence is preceded by the last one, and the last passenger is followed by the first one.  
For each passenger meeting the aforementioned criterion, display his/her name, the name of the previous passenger, and the name of the next passenger.  


<br>

### Exercise 127 
Find out the arithmetic mean (rounded to hundredths) of the following prices:  
\- Price of the cheapest Laptops produced by makers of PCs with the lowest CD-ROM speed;  
\- Price of the most expensive PCs by makers of the cheapest printers;  
\- Price of the most expensive printers by makers of Laptops with the greatest RAM capacity.  
Note: Exclude missing prices from the calculation.  


<br>

### Exercise 128 
For each existing pair of buy-back centers from different tables (outcome and outcome_o) having the same identifier, determine the one with a greater total daily payout for each date at least one member of the pair collected recyclables.  
Result set: buy-back center ID, date, one of the following messages:  
\- "once a day", if the center with only one payment per day possible has a greater payout;  
\- "more than once a day", if the payout is greater for the center with several transactions per day possible;  
\- "both", if both pair members paid out the same sum.  

<br>


### Exercise 129 
Assuming there are gaps in the sequence of ordered square IDs (Q_ID), find the minimum and maximum "free" values in the range between the least and the biggest existing IDs.  
E.g., for a square ID sequence consisting of 1, 2, 5, 7, the result should be 3 and 6.  
If there are no gaps in the sequence, display NULLs for both values.  

<br>


### Exercise 130 
Historians decided to make a summary of battles and arrange it in two super columns.   
Each super column consists of three columns containing the battle serial number, name, and date.  
First, the left super column is filled out in ascending order of serial numbers, then the right one.   
Serial numbers are assigned sequentially, with the battles being sorted by date, then by name.  
In order to save paper the historians distribute the data from the Battles table equally between the two super columns (adding an extra battle to the left one if the total of battles is odd).  
Display the result of the historians’ work as a six-column table, filling empty cells with NULL values.  


<br>

### Exercise 131 
Select cities from the Trip table whose names contain at least 2 different vowels from the list (a,e,i,o,u), with all these letters occurring an equal number of times in the name.  

<br>


### Exercise 132 
For the date of each battle (date1), take the date of the chronologically subsequent battle (date2); if there is no such battle, use the current date.  
Determine the age (the number of full years and full months) a person born on date1 reaches on date2.  
Notes:  
\- assume a full month of age is reached on the day matching the birthday, or earlier if the month in question doesn’t have any subsequent days; a full year consists of 12 full months; all battles took place on different dates before today.  
\- represent the dates in "yyyy-mm-dd" format without the time part, and the age in "Y y., M m." format; omit the number of years or months if the corresponding value is 0; display an empty string for an age of less than 1 full month.  

<br>


### Exercise 133 
Let S be a subset of the set of integers.  
Let’s call "a hill with N on its top" a sequence of members of S consisting of numbers less than N arranged in ascending order from left to right and concatenated to a string without delimiters, followed by the same numbers arranged in descending order, and the value of N lying in between.  
E. g., for S={1,2,...,10}, the hill with 5 on its top is represented as 123454321.  
Assuming S consists of all company identifiers, put together a hill for each company, with its ID forming the top of the hill.  
Consider all IDs to be positive and note there is no data in the database that can cause the hill sequence exceed 70 digits.  
Result set: id_comp, hill sequence  

<br>


### Exercise 134 
To make the squares white, additional paint of each color is applied to them according to the following scheme:  
\- first, squares needing the least amount of paint of a given color are dyed;  
\- in case the amount of needed paint is equal, squares with smaller Q_IDs are dyed first.  
Find the IDs of the squares that still AREN’T white after all of the paint has been used up.  
<br>



### Exercise 135 
For each one-hour interval starting on the hour during which squares were dyed, determine the last moment of a painting event (B_DATETIME).  

<br>


### Exercise 136 
For each ship in the Ships table whose name contains symbols that aren't letters of the English alphabet, display its name, 
the position of the first such non-alphabetic character, and the character itself.  


<br>

### Exercise 137 
For each fifth model (in ascending order of model numbers) in the Product table, find out its product type and average price.  

<br>


### Exercise 138 
Determine all unique pairs of non-black squares (q_id1 and q_id2) painted by the same set of spray cans.  
Output: q_id1, q_id2, where q_id1 < q_id2.  

<br>


### Exercise 139 
For each ship not present in the Outcomes table, obtain the comma-separated chronological list of battles it couldn’t have participated in. 
If there are no such battles, output NULL.  
Assume a ship could have taken part in any battle that happened in the year the vessel was launched.  
Output: ship name, list of battles.  

<br>


### Exercise 140 
For the period from the earliest battle in the database to the last one, find out how many battles happened during each decade.  
Result set: decade (in "1940s" format); number of battles.  

<br>


### Exercise 141 
For each travelled passenger, determine the number of days in April, 2003 lying between the dates of the passenger’s first and last departure inclusive.  
Display the passenger’s name and the number of days.  

<br>


### Exercise 142 
Among the passengers who only flew by the planes of the same model, find names of those who arrived at the same town at least twice.  

<br>


### Exercise 143 
For each battle, find out the date of the last Friday of the month this battle occurred in.  
Output: battle, date of battle, date of the last Friday of the month.  
Display the dates in "yyyy-mm-dd" format.  


<br>

### Exercise 144 
Get the manufacturers producing both the cheapest and the most expensive PCs.  


<br>

### Exercise 145 
For each pair of consecutive dates in the Income_o table denoted as dt1 and dt2, determine the sum of payments 
according to the Outcome_o table within the half-closed interval of dates (dt1, dt2].  
Output: sum of payments, dt1, dt2.  


<br>

### Exercise 146 
For the PC in the PC table with the maximum code value, obtain all its characteristics (except for the code) and display them in two columns:  
\- name of the characteristic (title of the corresponding column in the PC table);  
\- its respective value.  


<br>

### Exercise 147 
Number the rows of the Product table as follows: makers in descending order of number of models produced by them (for manufacturers producing an equal number of models, their names are sorted in ascending alphabetical order); model numbers in ascending order.  
Result set: row number as described above, manufacturer's name (maker), model.  


<br>

### Exercise 148 
In the Outcomes table, transform the names of the ships containing more than one space as follows: replace all characters between the first and the last spaces (excluding these spaces) by asterisks (\*).  
The number of asterisks has to be equal to the number of replaced characters.  
Result set: ship name, transformed ship name.  
<br>



### Exercise 149 
Determine the upper limit of the interval (B_DATETIME <= MinTime), during which each spray can in the utB table has been used at least once.  
Display the names of different spray cans being in use at this moment.  


<br>

### Exercise 150 
For each point in the Income table, determine the minimum (min_date) and maximum (max_date) dates of receiption of funds.  
In the time-ordered sequence of all records in the Income table for each interval [min_date, max_date] define one closest row above (date1 < min_date) and closest below (date2 > max_date).  
In other words, it is required to extend each interval by one row above and below. If the wanted row/rows are absent, consider the date1 / date2 value to be undefined (NULL).  
Output: point, date1, min_date, max_date, date2.  


<br>

### Exercise 151 
For each ship from the Ships table, determine the name of the earliest battle from the Battles table it could have participated in after being launched.  
If the year the ship has been launched is unknown use the latest battle.  
If no battles occurred after the ship was launched, display NULL instead of the battle name.  
It’s assumed a ship can participate in any battle fought in the year of its launching.  
Result set: name of the ship, year it was launched, name of battle.  
Note: assume there are no battles fought at the same day.  
<br>



### Exercise 152 
The Product table is considered. Printers sorted by model form groups (with models representing group numbers).   
PC models (sorted from the lowest model to the largest one) are added one by one to each printer's group (in ascending order).   
After another PC is added to the last group, the process is resumed from the first group, and goes on in the same manner till the PC models are exhausted.   
Number the records as follows: printer models according to group model, then PС models belonging to the group.  
Output: record number, model, type.  
Note. Laptop models should not be taken into account or displayed.  


<br>

### Exercise 153 
Find the names of different passengers who ever travelled twice in a row occupying seats with the same number.  

<br>


### Exercise 154 
Assume that in all tables the point field with the same number indicates the same point.  
For each point, calculate the amount of expense and income for each day when there were transactions with this item separately 
according to the tables with statements once a day and separately with reports several times a day.  
If on one day the item had operations both on reporting once a day and on reporting several times a day, then such data should not be output.  
Output: point, date, amount of receipt, amount of expense, 'once' - if the type of operation is once a day and 'several' if several.  
Note: If there is no income/outcome, output 0.  


<br>

### Exercise 155 
Assuming there is no flight number greater than 65535, display the flight number and its binary representation (without leading zeroes).  
<br>



### Exercise 156 
Distribute all squares in the utQ table into three columns (row by row) in ascending order of their IDs.  
If the last row turns out to be not filled completely use NULLs for the missing values. For example, for the ID sequence {1,2,3,4,5,6,7,8} the result should be  
1 2 3  
4 5 6  
7 8 NULL  

<br>


### Exercise 157 
For all ships in the database that haven't been sunk, find out the number of battles they participated in.  
Display the name of the ship, the number of battles.  


<br>

### Exercise 158 
For the Outcome table, get the difference of total payments per each day (out_over) in comparison to the average sum of payments for the previous two days payments occured on.  
Output: date, out_over  


<br>

### Exercise 159 
For each painting event (t,q,v,vol) = (B_DATETIME,B_Q_ID,B_V_ID,B_VOL), determine the previous painting of the 
same square with the same spray can and display it in the table (t,q,v,vol,tp,volp).  
If there was no such painting, then set tp and volp to NULL.  

<br>


### Exercise 160 
Output the names of passengers who have visited the largest number of different cities, including the cities of departure.  

<br>


### Exercise 161 
Output countries whose ships have never participated in any battle.  



