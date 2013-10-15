XLKit
=====

An iOS/OS X library for creating simple, stupid Excel XML documents (i.e. xlsx)

###Background

 Throughout my career I've encountered many situations where a client/employer has asked for data to be exported into a Simple Stupid Excel file.
 While I personally think Excel is one of the very worst things that has happened to data architecture since the Y2K mistake of the 1960's,
 I have to acknowledge that Excel is a file format used for interchange of data all over the world and it's not going away anytime soon.
 
 When I have worked on cross-platform teams where a mac and windows version were being simultaneously developed, my windows counterparts were always able use Microsoft's existing Excel library functionality to
 export Simple, Stupid Data to Simple, Stupid Excel Files. The Mac implementation I had to write, however,was at a deficit. I could find here no Simple, Stupid Library for mac library for exporting Simple, Stupid Excel Docuents.
 In most of these projects, the mac implementation had to default to the strategy of "have the client or customer export to .CSV files, and then import
 with our software." If we were lucky, we could use a third party web service to do the export to Excel.
 
 Both workarounds I find unacceptable for the following reasons:
 
 * Many non-technical users do not know what a .CSV file is.
 * A .CSV file does not by default have the tell-tale Excel icon that many non-technical users recognize.
 * Exporting to .CSV files requires a non-technical user to navigate through a maze of menus and know enough about Excel to accomplish this task.
 * Exporting to .CSV and importing to Excel can add a number of tedious extra steps even for a technical user.
 * A .CSV has the potential risk of not being recognized as an Excel document, because at the end of the day it's still a text document.
 * A .CSV that is opened has to be explicitly saved as an Excel file to be converted into a proper Excel file.
 * If Google or any other external third-party service decides to pull the plug on their web service, the user is left without an Excel export feature, and you or your company has to play the game of Blame The Vendor.
 * Any of these solutions violate my Horizon Methdology doctrine of Solve The Problem By Solving The Problem.

 
In writing this code, I hope to make life easier on myriad iOS/OS X developers, myself especially.


###Core Failure Statement

An essential element of my Horizon Methdology is the Core Failure Statement, which defines the most important tasks that the most important target audience
requires to validate the existence of the code in the first place. While software should certainly evolve, no change can ever be allowed that fundamentally violates the Core Failure Statement.


*XLKit is a failure if a comptetant Objective-C developer has to spend more than an hour to figure out how to create/export a non-styled three column, three row spreadsheet using the most basic XLKit classes.*

###Contributions/Feedback

Any feedback however good or bad is entirely encouraged. You're allowed to tell me that XLKit is the most wonderful programming library you've ever used, and likewise you're allowed to say
that XLKit is the worst piece of junk you've ever tried to use, and that I should retire from programming altogether and move to Tahiti to paint abstract nudes for the rest of my life.
The Horizon Methodology considers Freedom To Criticize Software to be Essential Software Freedom. Any reasonable feature request will be considered, provided it
stays within the bounds of the Core Failure Statement.

Similarly, any user is welcome and encouraged to contribute code and improve XLKit, again provided that the changes
stay within the bounds of the Core Failure Statement.
