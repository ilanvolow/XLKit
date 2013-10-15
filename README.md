XLKit
=====

An iOS/OS X library for creating simple, stupid Excel XML documents (i.e. xlsx)

###Background

 Throughout my career I've encountered many situations where a client/employer has asked for data to be exported into a Simple Stupid Excel file.
 While I personally think Excel is one of the very worst things that has happened to data storage since the Y2K mistake of the 1960's,
 I have to acknowledge that Excel is a file format used for interchange of data all over the world.
 
 While my windows counterparts working on cross platforms easily could use Microsoft's existing Excel functionality through COM, OLE, whatever,
 the mac implementation I had to write was at a deficit as there was no Simple, Stupid Library for creating Simple, Stupid Excel Docuents.
 In most of these projects, the mac implementation had to default to the strategy of "have the client or customer export to .CSV files, and then import
 with our software." If we were lucky, we could use a third party web service to do the export to Excel.
 
 These solutions were unacceptable for the following reasons:
 
 * Many non-technical users do not know what a .CSV file is.
 * Exporting to .CSV files requires a non-technical user to navigate through a maze of menus and know enough about Excel to accomplish this task.
 * A .CSV exported file has the possibility of being opened with a text editor instead of Excel because, after all, it's a .txt file.
 * Both exporting as well as importing .CSV create a number of tedious extra steps even for a technical user. Opening an Excel document requires only a mouse double-click on a file. The import/export solution can easily add six mouse click to accomplish the same goal. Mutiple six clicks by dozens of potential documents and you get a huge-pit of end-user annoyance.
 * If Google or any other external third-party service decides to pull the plug on their web service, the user is left without an Excel export feature.
 * Any of these solutions violate the Horizon Methdology doctrine of "Solve The Problem By Solving The Problem."
 
 In writing this code, I hope to make life easier on myriad iOS/OS X developers, myself especially.


###Core Failure Statement

An essential element of the Horizon Methdology is the Core Failure Statement, which defines the most important tasks that the most important target audience
requires to validate the existence of the code in the first place. While software should certainly evolve, no change can ever be allowed that fundamentally violates the Core Failure Statement.



*XLKit is an entire failure if an entry-level Objective-C developer requires more than three hours to create/export a non-styled three column, three row spreadsheet.*

###Contributions/Feedback

Any feedback however good or bad is entirely encouraged. You're allowed to tell me that XLKit is the most wonderful programming library you've ever used, and likewise you're allowed to say
that XLKit is the worst piece of junk you've ever tried to use, and that I should retire from programming altogether and move to Tahiti to paint abstract nudes for the rest of my life.
The Horizon Methodology considers Freedom To Criticize Software to be Essential Software Freedom. Any reasonable feature request will be considered, provided it
stays within the bounds of the Core Failure Statement.

Similarly, any user is welcome and encouraged to contribute code and improve XLKit, again provided that the changes
stay within the bounds of the Core Failure Statement.
