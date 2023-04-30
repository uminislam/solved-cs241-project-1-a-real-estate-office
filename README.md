Download Link: https://assignmentchef.com/product/solved-cs241-project-1-a-real-estate-office
<br>
<span class="kksr-muted">Rate this product</span>

PROJECT DESCRIPTION

A DBMS needs to be implemented for a real estate office, that sells houses and apartments within a city. The office needs to store a lot of data, specifically:

<ul>

 <li>agents: An agent is responsible for interacting with buyers and sellers, to show properties to them and facilitate sales or giving on rent.</li>

 <li>details of homes/apartments: The address, selling price, rent, details of the house (example: size: 1500 sq. ft, number of bedrooms: 2)</li>

</ul>

3 DATA GENERATION

You can see magicbricks.com, 99acres.com, makaan.com etc. for good examples of data.

4

PROJECT REQUIREMENTS

(1) E-R Model(a) Construct an E-R diagram representing the conceptual design of the database. (b) Be sure to identify primary keys, relationship cardinalities, etc.

(2) Relational Model

<ol>

 <li>(a)  After creating an initial relational design from your E-R design, refine it based on the principles of relationaldesign.</li>

 <li>(b)  Create the relations in MySQL.</li>

 <li>(c)  Create indices (indices will be taught later) and constraints as appropriate.</li>

 <li>(d)  If, as you refine your design, you discover flaws in the E-R design, go back and change it (even if the earlierdesign passed the checkpoint.) Your final E-R design must be consistent with your relational design.</li>

</ol>

(3) Populate Relations

(a) Include enough data to make answers to your queries interesting and nontrivial for test purposes.(4) Queries: Run enough queries to ensure that your database is populated the way you intended it to be. Given

below are the queries that you must demonstrate. You may be asked to demonstrate additional queries.

<ol>

 <li>(a)  Find addresses of homes in your city (for example Guwahati) with rent between Rs.20,000 and Rs. 40,000 permonth.</li>

 <li>(b)  Find details of homes for rent in G.S.Road (you can use the name of another locality if your city is different)</li>

</ol>

.

with at least 2 bedrooms and costing less than Rs.10,000 per month. Show the contact number(s) of agents who can show you these properties.

1

2

(c) Find the name of the agent who has sold the most property in the year 2021 by total amount in rupees.

<ol start="4">

 <li>(d)  Find the addresses of homes in your city that are available for sale and that has at least 2 bed rooms. List theasking price and the number of bedrooms, with other details that may be necessary.</li>

 <li>(e)  List the details of the most expensive houses and the houses with the highest rent, in the database.</li>

</ol>

(5) Interfaces: There are two types of users who access the database. Each may need a different interface:

<ol>

 <li>(a)  The database administrator (you) may use SQL via the command line.</li>

 <li>(b)  The real estage agent’s office, to get 1) sales reports for each agent, consisting of the sale dates, property detailsand selling price and 2) how many properties have been given on rent by each agent for what amount, inwhich area, when.</li>

 <li>(c)  Agents, to update the database when a property is rented or sold.</li>

</ol>

These interfaces can be built as 1) Web applications using Java applets or a scripting language. 2) A standalone Java application using Swing to create a GUI 3) A standalone Java application with a command line interface 4) Any other GUI tool you may know

(6) Concurrency: The database must support more than one agent accessing the database at a time along with someone from the real estate office. Make sure that the required guarantees are provided.

5 DELIVERABLES

For each deliverable, the contribution of each team member must be stated. If a person’s contribution is not stated, it will be assumed that that person has not contributed.

The last date for each item is as given below:

<ol>

 <li>(1)  ER diagram, with assumptions, in a document – March 25, 2021 (maximum two pages)</li>

 <li>(2)  Relational design, user interfaces and their features, in a document – April 1, 2021 (Provide the SQL tables andtheir primary and foreign keys)</li>

 <li>(3)  Interface for the database administrator with all the queries working, as demo – April 8, 2021.</li>

 <li>(4)  Interface for real estate office and agents, as demo – April 15, 2021.</li>

</ol>