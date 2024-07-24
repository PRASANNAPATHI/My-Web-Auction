# Web Auction Application

A auctioning system with a backend database and a Web front-end.

Item registration, auctioning, searching and bidding (using servlets, JSP for the front-end, and EJBs for the middleware).

The software architecture implements is MVC (Model-View-Controller).

The database that is used is MySQL and has 4 tables for storing the description of auction items, personal information about the bidders, operational information about the auctions and historical information about the bids (i.e., USER, ITEM, AUCTION, BID). 

The user will have the ability to log into the system.  The user will have the ability to create an auction on the web application with the description of the item and the start price for the auction.  Once submitted, the web application will add the item to the database and automatically start the auction for that specific item. The user can search for auctions in the system The user can make a bid on an auction.  The admin can remove an auction from the system.(Admin)
