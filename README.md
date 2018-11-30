# Week8-Codepath
Week 8 Codepath Assignment

Required exploits:

Username enumertion
Insecure direct object reference
SQL injection (SQLi)
XSS (Cross site scripting)
Cross site request forgery
Session Hijacking

- located in the blue target:

#1 Username Enumeration 
<a href="https://imgur.com/NQyyVFS"><img src="https://i.imgur.com/NQyyVFS.png" title="source: imgur.com" /></a>
Vulnerability Number 1: It only works under the find a salesperson tab, and was opening was after the id="" for the salesperson that I selected.


#2 Session Hijacking - There is a hidden php form used to change the session id. Using this form an attacker can change the session id to one that is currently logged in, bypassing login security.
<a href="https://imgur.com/Rc6otQH"><img src="https://i.imgur.com/Rc6otQH.png" title="source: imgur.com" /></a>

- located in the Red target:

#1 Insecure direct object reference 
<a href="https://imgur.com/HyDkHpw"><img src="https://i.imgur.com/HyDkHpw.png" title="source: imgur.com" /></a>
Again there is an exposed id number in the url which can be changed to find hiden users.

#2 Cross site request forgery - 
It is possible to create a hidden form that is able to change salesperson data, resulting in a cross-site request forgery exploit, below is the form:
<a href ="https://imgur.com/b0n41N6"><img src = "https://i.imgur.com/b0n41N6.png" title = "" /></a>

- located in the Green target:

#1 User enumeration 
If you type in a username that exists then the page gives a bold response. This lets you know what usernames are in the database.
<a href="https://imgur.com/JbkR1Me"><img src="https://i.imgur.com/JbkR1Me.png" title="source: imgur.com" /></a>

#2 XSS 
The form allows an attacker to store a script that will be activated by the next logged in user that is checking the feedback response submissions. This simple script is just a popup box that displays the message I entered, some seriously harmful attacks can be done using this form.
<a href="https://imgur.com/NGljCvI"><img src="https://i.imgur.com/NGljCvI.png" title="source: imgur.com" /></a>












