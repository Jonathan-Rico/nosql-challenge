# nosql-challenge

The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. 
We have been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

Using the data provided in the establishments.json file, we use the terminal to import the data into a MongoDB database. Using Python's PyMongo library, we confirm that the database and collection we imported from the terminal were created on our local system. In addition, we make updates to the database to add a new entry provided to us, as well as remove existing entries which contain establishments in Dover. We also make changes to the documents to update the data type from the latitude and longitude values to vbe converted from strings to decimal numbers.

In our exploratory analysis, we use specific queries to answer the following questions:

Question 1: Which establishments have a hygiene score equal to 20?

--The Chase Rest Home,Brenalwood, Melrose Hotel	, Seaford Pizza	, Golden Palace, Ashby's Butchers, South Sea Express Cuisine, Golden Palace	, The Tulip Tree and F & S are a few of the restaurants which have a hygiene score of 20.

Question 2: Which establishments in London have a RatingValue greater than or equal to 4?

--Charlie's, Mv City Cruises Erasmus, Benfleet Motor Yacht Club, Coombs Catering t/a The Lock and Key, Tilbury Seafarers Centre	, Mv Valulla, Tereza Joanne	, Brick Lane Brews are some of the London establishments which have a rating value greater than or equal to 4.

Question 3: What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

--Volunteer, Plumstead Manor Nursery , Atlantic Fish Bar, Iceland, Howe and Co Fish and Chips - Van 17	are the top 5 establishments which meet both of the criteria above and are near the new restaurant "Penang Flavours".

Question 4: How many establishments in each Local Authority area have a hygiene score of 0?
The top 10 Local Authority areas which have a hygiene score of 0 are:
--
Count  Area
1130	Thanet
882	  Greenwich
713	  Maidstone
711	  Newham
686	  Swale
680	  Chelmsford
672	  Medway
607	  Bexley
586	  Southend-On-Sea
542	  Tendring
--
