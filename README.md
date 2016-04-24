This is the sample test methods for html page that using single page application method
to talk to the web server.
The methods are supplied by jquery.min.js that located in bower_components\jquery\dist.

1) get.html is using simple ajax method to get the content of a raw txt file from demo_test.txt


2) ajax_get.html is using jquery ajax methods to send an ajax request to talk to the server side
   php program (display.php) which connect to mysq database by connection.php and response the 
   contents back to client html page asynchronously .

   This test ajax directory produce two kinds of methods to test how ajax works

1) html get raw txt file in the Server
   get.html
   demo_test.txt

2) html get mysql database by sending ajax call to server php file (display.php)
   ajax_get.html , using jquery ajax call to manage the ajax task
   
   connection.php, to be put at the same folder for the include statement in side
   display.php.

   dispay.php, Server side php to be call by ajax from ajax_get.html and response
   to the mysql database.

 All file have to put inside a sub directory (jquery) of your www root i.e. /jquery

 test  get.html -> http://your-server-ip/jquery/get.html
 
 test ajax_get.html -> http://your-server-ip/jquery/ajax_get.html

 the student.sql should be imported into your Mysql database before you test this ajax get task


 jquery.min.js


