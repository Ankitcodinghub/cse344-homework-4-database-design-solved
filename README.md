# cse344-homework-4-database-design-solved
**TO GET THIS SOLUTION VISIT:** [CSE344 Homework 4: Database Design Solved](https://www.ankitcodinghub.com/product/cse344-homework-4-database-design-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;53887&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE344 Homework 4: Database Design Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<strong>Objectives:</strong>&nbsp;To translate from entity relationship diagrams to a relational database, and to understand functional dependencies and normal forms.

<strong>Assignment tools:</strong>

<ul>
<li>Pen and paper or any drawing tools you prefer (e.g., powerpoint,&nbsp;<a href="https://www.draw.io/" rel="nofollow">draw.io</a>).</li>
<li>SQLite, Azure SQL Server, or any other relational database.</li>
</ul>
<h2><a id="user-content-assignment-details" class="anchor" href="https://github.com/theoliao1998/Data-Management/blob/master/4%20Database%20Design/hw4.md#assignment-details" aria-hidden="true"></a>Assignment Details</h2>
<h3><a id="user-content-part-1-flight-booking-service-er-design-30-points" class="anchor" href="https://github.com/theoliao1998/Data-Management/blob/master/4%20Database%20Design/hw4.md#part-1-flight-booking-service-er-design-30-points" aria-hidden="true"></a>Part 1: Flight Booking Service E/R Design (30 points)</h3>
Congratulations, you are opening your own flight booking service! In this homework, you will create an Entity-Relationship (E/R) diagram for a database to support your booking service. In the next homework, you will implement your booking service as a Java program. Think hard on this problem as it will inform the design you implement in the next homework.

The following is a description of the domain and tasks your flight booking service needs to support. Read this description, then decide on entities and relationships for a database to support your service.

This service is based on the tables Flights, Carriers, Months, and Weekdays used in hw2 and hw3. Please see hw2 for a reminder of their schema.&nbsp;<strong>Your flight booking service may not modify the contents of Flights, Carriers, Months, or Weekdays</strong>, because updates to these tables (such as scheduling new flights) occur outside of your application.

Your service follows a&nbsp;<a href="https://en.wikipedia.org/wiki/Client%E2%80%93server_model" rel="nofollow">client-server model</a>. Users interact with your service by running your client application. Savvy, frequent-flyer users may run several instances of your client application at once! The client application can either:

<ol>
<li>store information locally (just inside the client program) and transiently (not saved after the program closes), in which case this information does not need to be stored in a server database.</li>
<li>store information globally (accessible to all client programs) and persistently (saved after the program closes), in which case this information needs to be stored in a server database.</li>
</ol>
Remember that only data that falls under category 2 need be stored in your database and modeled in your entity-relationship diagram.

<h4><a id="user-content-service-requirements" class="anchor" href="https://github.com/theoliao1998/Data-Management/blob/master/4%20Database%20Design/hw4.md#service-requirements" aria-hidden="true"></a>Service Requirements</h4>
Users&nbsp;<em>create an account</em>&nbsp;in your service by specifying their&nbsp;<em>username</em>&nbsp;(case insensitive), a&nbsp;<em>password</em>&nbsp;(case sensitive), and an&nbsp;<em>initial balance</em>. Balances are given in dollars, and are used to pay for booking flights.

After creating an account, a user may&nbsp;<em>login to their account</em>&nbsp;by specifying their&nbsp;<em>username</em>&nbsp;and&nbsp;<em>password</em>.

A user may make a&nbsp;<em>deposit to their account</em>&nbsp;by specifying&nbsp;<em>how much money</em>&nbsp;they wish to add to their balance.

Anyone (even users that have not logged in) may&nbsp;<em>search for flight itineraries</em>. In this context, a flight itinerary is either a&nbsp;<em>direct flight itinerary</em>, in which case it consists of a single flight, or a&nbsp;<em>one-stop flight itinerary</em>, in which case it consists of two flights (which must both occur on the same day, and where the destination of the first flight matches the origin of the second flight).

To search for a flight itinerary, a user specifies an&nbsp;<em>origin city</em>, a&nbsp;<em>destination city</em>, a&nbsp;<em>flight date</em>, a&nbsp;<em>maximum number of itineraries to display</em>, and&nbsp;<em>whether they only wish to search for direct flights</em>&nbsp;or whether they are open to one-stop flights.

A logged-in user may try to&nbsp;<em>book a flight itinerary that they searched for</em>. To do so, the user specifies an&nbsp;<em>itinerary from their most recent search</em>. They may book the itinerary as long as there remains capacity on all flights contained in the itinerary. That is, if one of the flights a user wishes to book has no capacity remaining (because other users already made reservations for that flight), then the booking is not allowed. If the reservation is successful, it is recorded in the database that the user that booked it.

A user may later&nbsp;<em>pay for their reservation</em>. In order to pay, the user must have enough balance in their account to afford the flight’s price.

Alternatively, users may&nbsp;<em>cancel reservations</em>&nbsp;(either paid or unpaid). A canceled reservation is deleted, as if it never occurred, and any money paid is refunded to the user’s balance.

<h4><a id="user-content-er-diagram" class="anchor" href="https://github.com/theoliao1998/Data-Management/blob/master/4%20Database%20Design/hw4.md#er-diagram" aria-hidden="true"></a>E/R Diagram</h4>
From the above description, determine entities, relationships, and attributes you need to consider in order to support your service’s operations. Write these in an E/R diagram. Include primary keys on all entities. Include constraints on relationship connectors where appropriate.

<em>You are not required to list the non-key attributes of Flights, Carriers, Months, or Weekdays, since these are given in hw2.</em>&nbsp;All other entities must have attributes as well as primary keys listed.

You may draw your E/R diagram on paper and scan it, take&nbsp;<em>quality</em>&nbsp;pictures of your drawn diagram, or use your favorite drawing tool such as Powerpoint, Keynote, or&nbsp;<a href="https://www.draw.io/" rel="nofollow">draw.io</a>. (FYI: Google Slides lacks a few shapes that you might need such as rounded arrows… you can use a crescent and a line).

Name your file&nbsp;<code>hw4-flightapp.pdf</code>. If you choose to take a picture, please use the tool&nbsp;<a href="https://imagetopdf.com/" rel="nofollow">https://imagetopdf.com</a>&nbsp;to convert your image to a pdf.

<h3><a id="user-content-part-2-er-to-schema-20-points" class="anchor" href="https://github.com/theoliao1998/Data-Management/blob/master/4%20Database%20Design/hw4.md#part-2-er-to-schema-20-points" aria-hidden="true"></a>Part 2: E/R to Schema (20 points)</h3>
Consider the following E/R diagram:

<a href="https://i0.wp.com/github.com/theoliao1998/Data-Management/blob/master/4%20Database%20Design/figs/hw7-er/Slide1.jpg?ssl=1" target="_blank" rel="noopener noreferrer"><img data-recalc-dims="1" decoding="async" data-src="https://i0.wp.com/github.com/theoliao1998/Data-Management/raw/master/4%20Database%20Design/figs/hw7-er/Slide1.jpg?w=980&amp;ssl=1" alt="" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" class="lazyload"></a>

<em>License plate</em>&nbsp;can have letters and numbers;&nbsp;<em>driverID</em>&nbsp;and&nbsp;<em>Social Security</em>&nbsp;contain only numbers;&nbsp;<em>maxLiability</em>&nbsp;is a real number;&nbsp;<em>year</em>,&nbsp;<em>phone</em>,&nbsp;<em>capacity</em>&nbsp;are integers; everything else are strings.

a. (10 points) Translate the diagram above by writing the SQL&nbsp;<code>CREATE TABLE</code>&nbsp;statements to represent this E/R diagram. Include all key constraints; you should specify both primary and foreign keys. Make sure that your statements are syntactically correct (you might want to check them using SQLite, Azure SQL Server, or another relational database).

b. (5 points) Which relation in your relational schema represents the relationship “insures” in the E/R diagram? Why is that your representation?

c. (5 points) Compare the representation of the relationships “drives” and “operates” in your schema, and explain why they are different.

Write your answers in a SQL file named&nbsp;<code>hw4-driving.sql</code>. Write your answers to questions b and c as&nbsp;<em>SQL comments</em>&nbsp;in the same file.

<h3><a id="user-content-part-3-functional-dependency-theory-15-points" class="anchor" href="https://github.com/theoliao1998/Data-Management/blob/master/4%20Database%20Design/hw4.md#part-3-functional-dependency-theory-15-points" aria-hidden="true"></a>Part 3: Functional Dependency Theory (15 points)</h3>
A set of attributes X is called closed (with respect to a given set of functional dependencies) if X⁺ = X. Consider a relation with schema R(A,B,C,D) and an unknown set of functional dependencies. For each closed attribute set below, give a&nbsp;<em>set of functional dependencies</em>&nbsp;that is consistent with it.

a. (5 points) All subsets of {A,B,C,D} are closed.

b. (5 points) The only closed subsets of {A,B,C,D} are {} and {A,B,C,D}.

c. (5 points) The only closed subsets of {A,B,C,D} are {}, {B,C}, and {A,B,C,D}.

Write your answers in a text file named&nbsp;<code>hw4-theory.txt</code>.

<h3><a id="user-content-part-4-mr-frumble-relationship-discovery--normalization-35-points" class="anchor" href="https://github.com/theoliao1998/Data-Management/blob/master/4%20Database%20Design/hw4.md#part-4-mr-frumble-relationship-discovery--normalization-35-points" aria-hidden="true"></a>Part 4: Mr. Frumble Relationship Discovery &amp; Normalization (35 points)</h3>
<a href="http://everythingbusytown.wikia.com/wiki/Mr._Frumble" rel="nofollow">Mr. Frumble</a>&nbsp;(a great character for small kids who always gets into trouble) designed a simple database to record projected monthly sales in his small store. He never took a database class, so he came up with the following schema:

<code>Sales(name, discount, month, price)</code>

He inserted his data into a database, then realized that there was something wrong with it: it was difficult to update. He hires you as a consultant to fix his data management problems. He gives you this file&nbsp;<a href="https://courses.cs.washington.edu/courses/cse344/mrFrumbleData.txt" rel="nofollow">mrFrumbleData.txt</a>&nbsp;and says: “Fix it for me!”. Help him by normalizing his database. Unfortunately you cannot sit down and talk to Mr. Frumble to find out what functional dependencies make sense in his business. Instead, you will reverse engineer the functional dependencies from his data instance.

<ol>
<li>Create a table in the database and load the data from the provided file into that table; use SQLite or any other relational DBMS if your choosing.Turn in your create table statement. The data import statements are optional (you don’t need to include these).</li>
<li>Find all nontrivial functional dependencies in the database. This is a reverse engineering task, so expect to proceed in a trial and error fashion. Search first for the simple dependencies, say name → discount then try the more complex ones, like name, discount → month, as needed. To check each functional dependency you have to write a SQL query.Your challenge is to write this SQL query for every candidate functional dependency that you check, such that:a. the query’s answer is always short (say: no more than ten lines – remember that 0 results can be instructive as well)b. you can determine whether the FD holds or not by looking at the query’s answer. Try to be clever in order not to check too many dependencies, but don’t miss potential relevant dependencies. For example, if you have A → B and C → D, you do not need to derive AC → BD as well.Please write a SQL query for each functional dependency you find along with a comment describing the functional dependency. Please also include a SQL query for at least one functional dependency that does not exist in the dataset along with a comment mentioning that the functional dependency does not exist. Remember, short queries are preferred.</li>
<li>Decompose the table into Boyce-Codd Normal Form (BCNF), and create SQL tables for the decomposed schema. Create keys and foreign keys where appropriate.For this question turn in the SQL commands for creating the tables.</li>
<li>Populate your BCNF tables from Mr. Frumble’s data. For this you need to write SQL queries that load the tables you created in question 3 from the table you created in question 1.Here, turn in the SQL queries that load the tables, and count the size of the tables after loading them (obtained by running&nbsp;<code>SELECT COUNT(*) FROM Table</code>).</li>
</ol>
Write your answers in a SQL file named&nbsp;<code>hw4-frumble.sql</code>. Don’t forget to use SQL comments for all non-SQL-code answers.
