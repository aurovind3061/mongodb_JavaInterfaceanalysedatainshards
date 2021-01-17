# mongodb_JavaInterfaceanalysedatainshards
Call Data Operations and Analysis in Sharded Environment 
ABC Corp is a famous telecom company. They have customers in all locations. Customers use ABC Corp’s network to make calls. Government has brought in a regulation that all telecom companies should store call details of their customers. This is very important from a security point of view and all telecom companies have to retain this data for 15 years. ABC Corp already stores all customer details data, for their analytics team. But due to a surge in mobile users in recent years, their current database cannot handle huge amounts of data. Current database stores only six months of data. ABC Corp has discussed this problem with database experts and has set up MongoDB cluster. Now they are building a Java base interface which can help them store this data in MongoDB.

Data contains following columns
1.	Source : Phone number of caller
2.	Destination : Phone number of call receiver
3.	Source_location : Caller’s city
4.	Destination_location : Call receiver’s city
5.	Call_duration : Phone call duration
6.	Roaming :  Flag to check if caller is in roaming
7.	Call_charge : Money charged for call
Sample Data:
{
source: “+919612345670”,
destination: “+919612345671”,
source_location: “Delhi”,
destination_location: “Mumbai”,
call_duration: 2.03,
roaming: false,
call_charge: 2.03
}

You have been hired to build Java interface for MongoDB and perform the following tasks.

1.	Interact with the sharded system using Java application.
2.	Insert new documents from Java application for different sources in the database and see if data is distributed on different shards.
3.	Find total call charges for all records and its query behavior.
4.	Find number of calls made from each location and its query behavior.
5.	Find revenue generated for each location and its query behavior.
6.	Check total number of calls made from roaming (Roaming = true) and its query behavior.

