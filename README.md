<?php

if(!file_exists("testiweb.php"))
{
	die("File absent");
}
else
{
	$f=fopen("testiweb.php","r");
	print"file is present and ready for working";
}
?>
