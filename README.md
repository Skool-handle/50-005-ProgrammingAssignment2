# 50-005 Programming Assignment 2
Simple Server-Client codes.
Initate classes, and pass in the arguments as required. Given how insecure the code is, i'm not documenting it.<br>
<br><br>
Change of plans. Guess I am. <br>
To make it work in an IDE like intellij, please place it into the outermost folder<br>
For the rest, usual commandline compile please.<br>
<br><br><br>
#PROGRESS TRACKER
Create file sending code -check <br>
Create file receiving code -check <br>
Create appropriate parts to make it actually run -check <br>

#Debug code - in progress... will be updated with new horrible things found.
Fix their horrible send and receive code - check<br>
<br>note: apparently you should just send the entire expected filesize and CUT as soon as required.<br>
don't do their stupid flag method that just screwed it all over<br>
<br>figure out the total length of an encrypted file, send it over as the expected total bytes.<br>
Complete verification for certificate both ways. ie. hash a preset message. you could randomise the message but that seems like extra effort with little reward.<br>
Padding issue.<br>