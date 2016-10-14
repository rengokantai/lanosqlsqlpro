# lanosqlsqlpro
##1. Why change?
###1 The changing landscape of data

###4 What is a NoSQL database
In order to work with non-relationable and highly scalable data they do give up some of the characteristics that are found in relational databases. Most notably, transactional consistency of the data. So the data, because it's scaled can be in an inconsistent state.

##6. Case Studies and Scenarios
###1 Applying NoSQL choices via business scenarios
velocity - how frequently this is produced

###2 Working with hardware log files

###3 Storing customer or donor information
Justification:
- Realtime queries
- High data growth
- Big volume and velocity, no variety  

Use this type of NoSQL:  
Spark


###4 Tracking social gaming purchases
When are in game purchases made?  
Justification
- complex predictive queries  
- predictable volume of data
- Huge volume and velocity,somw variety  

Use this type of NoSQL:  
Spark


###5 Linking museum data
Where can patrons view works by families of painters  
it's very specific to the domain in which it's being asked, and the domain is art museums.  
Sourec data:  
- captured in a variety of locations 
- semi-structured, linked data  
- 2TB world-wide  
- data growth is small  


Justification
- Complex path and reflexicw queries  
- predictable volume of data  
- small volume and velocity  

Use this type of NoSQL:  
Graph

###6 Working with health data
Data:
variety of types:
- file data
- binary data
- metadata  
%GB, data growth is huge, cannot store in public cloud  

Justification:
- queries must be verified  
- complex data
- predicable volume of data
- small volume and velocity
- big variety  

Use this type of NoSQL:  
RDBMS(transactions)

##7. Important Tips
###1 Database selection tips for startups

###2 Considering how data will be input (ingested)
Sometimes NoSQL is not the right choice because it doesn't scale large enough. Use Hadoop because of the data volumes. So, again, considering the Vs, the volume, velocity, variety, and voracity is key to deciding whether and which NoSQL database to use.

###3 Considering how data will be output (queried)
The cost of Schema on read:
- The most important V: veracity  
