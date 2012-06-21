<?php
 $conectar = mysql_connect("localhost") or die (mysql_error());
	mysql_select_db("usuarios", $conectar);
	mysql_query("SET NAMES utf8");
	return $conectar;
	






?>
