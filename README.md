 
!DOCTYPE html>
<head>
<title>Password Protected</title>
<SCRIPT>
function passWord() {
var testV = 1;
var pass1 = prompt('Please Enter Your Password',' ');
while (testV < 3) {
if (!pass1) 
history.go(-1);
if (pass1.toLowerCase() == "yolo") {
alert('Welcome Anand Aggarwal or some friend of his!!');
window.open('home.html');
break;
} 
testV+=1;
var pass1 = 
prompt('Access Denied - Password Incorrect, Please Try Again.','Password');
}
if (pass1.toLowerCase()!="password" & testV ==3) 
history.go(-1);
return " ";
} 
</SCRIPT>
<FORM>
<input type="button" value="Enter Password" onClick="passWord()">
</FORM>
</CENTER></head>
<body>This page allows you to login to my site. Please enter the password you have been told and enter it in the box.
<!-- Free Web Hosting Area Start -->
<script type="text/javascript" src="http://user99.freewebhostingarea.com/a/conad.js"></script>
<script type="text/javascript" src="http://user99.freewebhostingarea.com/a/inline3xx.js"></script>
<br /><center><script type="text/javascript" src="http://user99.freewebhostingarea.com/a/in728.js"></script></center>
<center><a target="_blank" href="http://www.freewebhostingarea.com"><img src="http://user99.freewebhostingarea.com/i/freehosting.png" border="0" width="88" height="15" alt="Free Web Hosting" /></a></center><br />
<script type="text/javascript" src="http://user99.freewebhostingarea.com/a/zab.js"></script>
<noscript><br /><center><font color='#000000' face='Verdana' style='font-size: 11px; background-color:#FFFFFF'><a target='_blank' href='http://www.freewebhostingarea.com'><font color='#000000'>Free Web Hosting</font></a></font></center></noscript>
<!-- Free Web Hosting Area End -->
</body>
</html>
