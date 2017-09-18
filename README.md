# RevolutAssignment
Design and implement a RESTful API (including data model and the backing implementation) for money transfers between internal users/accounts.

Pre set up data: 
AccountNumber : 1
AccountNumber : 2

API for Viewing balance:
GET: localhost:8888/account/viewBalance/1

API for Topping up account balance
PUT: localhost:8888/account/topup/1/5000

API for money transfer from account1 to another account
POST: localhost:8888/account/transfer/1/2/500


running the jar:
java -jar /target/restWS-0.0.1-SNAPSHOT.jar