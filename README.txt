OBJECTIVE:
An ASMX web service and a web client is created to simulate a stock exchange and a user customizable stocks ticker. 

SPECIFICATIONS:
An ASMX web service is created to simulate a stock exchange.
	1. This service exposes a method for returning stock prices for a list of stock codes. Each stock price is a random integer between 1 to 1000. 
	2. The ASMX service is secured. Apply security so that only authorized clients can call it. You may choose any form of security. 

A web application is created where each user can maintain a stocks ticker. 
	1. User could register thenselves. 
	2. Users should be able to login.  
	3. Users can add or delete stock codes to their personalized list. 
	4. Users can see their stock codes along with their current prices. The prices are taken from the stock exchange service. The price should auto refresh every 10 seconds. 
	5. Applied input validations and constraints wherever necessary to create a stable application. 
	6. The web application uses the service exposed security mechanism to connect to it. 
	7. Created a database where user stocks list is stored. 


