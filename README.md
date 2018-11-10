# Week8CodePath
(Vulnerability #1: SQL Injection )

<a href="https://imgflip.com/gif/2m8622"><img src="https://i.imgflip.com/2m8622.gif" title="made at imgflip.com"/></a>

I performed a SQL injection at the public/staff/salespeople/show.php?id=? endpoint. The ? was replaced with the following SQL syntax: ' OR SLEEP(5)=0--' .This snippet forced the SQL query (and thus our entire request) to pause for 5 seconds, thus indicating a successful injection.


(Vulnerability #1: XSS )

<a href="https://imgflip.com/gif/2m86bg"><img src="https://i.imgflip.com/2m86bg.gif" title="made at imgflip.com"/></a>

This exploit is done via the feedback section.
The XSS executes when a privileged user accesses the feedback page in the feedback (logged in)


(Vulnerability #2: User Enumeration )

<a href="https://imgflip.com/gif/2m86e1"><img src="https://i.imgflip.com/2m86e1.gif" title="made at imgflip.com"/></a>

Using the given username "jmonroe99" we can see that a valid username shows a bold error.
An incorrect username shows a not-bolded error.


Bonus Objective 

<a href="https://imgflip.com/gif/2m86ih"><img src="https://i.imgflip.com/2m86ih.gif" title="made at imgflip.com"/></a>

On this attack by submitting this form using script tags in the contact us section. I was able to redirect to admin user to "google.com" 


(Vulnerability #1: User Enumeration )

<a href="https://imgflip.com/gif/2m86kj"><img src="https://i.imgflip.com/2m86kj.gif" title="made at imgflip.com"/></a>

By directly changing the 'id' parameter in the URL we can find salespersons not mentioned on the page.
ID's 10 and 11 shouldn't be accessible by everyone.


