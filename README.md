# CyberTest-01
A web scripts for a company cyberTest based in an event.

In this case, an Web Index.html has been created, and that page simulate a NextCloud company Login Screen.
That web page send an solicitation for the python server, and that solicitation is registrated with a timelocal and local ip address in the MySQL DB.

In the web page, when the user put the username and the password, another solicitation is send to the python server, in another route, and this solicitation register too in the DB de timelocal and the user and password that user put in.

That script can be changed by the ambient of the corporation.

To send to the user, is needed to creat an virtual enviroment, and send the ip address to the user. In this ocasion, only function on the same network, but can be creat an virtual host to function on diferents lans.
