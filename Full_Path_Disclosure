<?php
   echo file_get_contents(getcwd().$_GET['page']);
?>

<?php
   //Hidden configuration file containing database credentials.
   $hostname = 'localhost';
   $username = 'root';
   $password = 'owasp_fpd';
   $database = 'example_site';
   $connector = mysql_connect($hostname, $username, $password);
   mysql_select_db($database, $connector);
?>
