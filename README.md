# Bus_Companion
/*A web app to make travelling by buses easier, faster and more comfortable.*/

With rapid increase in population, public transportation is best mode of travel for developing nations like India. Indian government is focusing more on digitizing the nation. There are not plenty of accessible WiFi zones at public places and in public transports like that of in developed nation.
“e-Travel Companion” is an idea of enhancing the accessibility of a traveller while travelling especially when he/she is travelling alone in a new place. This app will enable a user to book and pay for journey; access the media content (movies, TV shows, etc.) provided by the portal inside bus or metro; get the details of journey (location, next stop, time and distance remaining, etc.).


Bus Companion is a web application for simplifying local travel through public transport, especially busses. The project currently focuses on travel through busses but its scope can later be expanded to various other transport methods like trains and taxis. The web application acts as a complete guide for any person travelling on public busses as it assists them in knowing which bus to take, booking a ticket online, WiFi services on the bus and live location of the bus while they are on it which helps the person to estimate the remaining travel time.
The project consists of 5 main modules which can be listed as follows:
1.	Bus search
2.	Online booking
3.	RFID card to travel and use the services available
4.	Media content provided once connected to the bus server
5.	Notification system to alert one of their upcoming destination stop.


Bus Search

The user can enter their source, destination of travel and the timing in the application which will then suggest the bus number and nearest bus timing to that specified by the user. For the implementation of this module, we can use web scraping and obtain information from the front end of various state transport websites and store it in our database.

Online Booking

This module will allow the user to book a ticket for the bus of their choice by paying online through net banking, debit card details, Paytm etc. This can be implemented by redirecting the user to the website of the state and paying there.

RFID Cards

Regular users of the transport system will be issued RFID cards with a balance in them obtained on payment of that amount. These can be read by readers on the bus to allow the user for travelling on that bus and availing various services such as live location and access the media offered.
 
Media Content and Live Location

The users will be offered various media content once they have boarded the bus and have connected to the bus server. They can also use the live location feature implemented using GPS module. This will help them to track their positions in real-time.

Notification System

Once a user is connected to the bus server and their destination details are known, this module will alert the user of their upcoming stop by sending a notification to their device through which they are connected. Never again will a person miss their stop due to any reasons such as dozing off, confusion etc.
 
