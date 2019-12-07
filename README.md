# intern_task

so here im explain this tasks modules by modules
<br>
# register modules
 <br>
register modules contain 
1. register.html
2. register.js 
3.  reg1.php
4.  reg2.php

> register.html 
will collect the datas from user and pass it to `reg1.php` and `reg2.php` using `register.js` with `AJAX`
`reg1.php`will check username is already excit or not if not will pass to `reg2.php` otherwise an alert message
`reg2.php` willstore the datas in database . mysql was designed in prepared statements
<br>

# login modules
 <br>
login modules contain 
1. login.html
2. login.js 
3.  log.php
<br>


> login.html 
will collect the datas from user and pass it to `log.php` using `login.js` with `AJAX`
`log.php`will check username and password  if both match  session will start and pass to profile , otherwise alert message

<br>

# profile
 <br>
profile modules contain 
1. profile.html
2. profile.js 
3.  profile1.php
<br>

> profile.html 
will catch the username from session and display the profile to user. if user need to update is profile he can update it my clicking 
update button .so here `update.html`page opens, `update.js` and  `updateplace.php` will update the data that user entered

#json.php
to store user data in json form

