`elephants`

What is?
========

`elephants` is about keeping track of what you're doing to have a continous memory of your day.  It's like the narcissism of twitter, but for your eyes only.

Why CouchDB?
------------
No reason.  It's hip and happening now.  You could use anything as the database.  You're just saving timestamps and strings at the moment.  It could use a csv for all I care.  I'd like to refactor it so that the database layer is appropriately abstracted away so you could use anything, but I'm short on time lately.

Why not... MongoDB?
___________________

I found a free couchdb host first.  And the couchdb wiki claims that a default install gets an easy-to-import javascript API.  Since the focus of this is to get an easily portable data logger that I can use at any computer this seemed like the path of least resistance.

Installing
==========
Ideally this is a single html file-- maybe supplimentary javascript file as well.  The plan is to have it be that you can connect to any default couchdb setup and start right away.  Perhaps there will be some sort of a cookie or HTML5 thing to remember where your database is, or an extra javascript file that can be saved in the same directory to make sure you always get an easy pointer to the database.
