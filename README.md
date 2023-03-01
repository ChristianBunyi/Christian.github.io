<!DOCTYPE html>
<html>
<head>
	<title>Gaming Landing Page</title>
	<meta charset="utf-8"/>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="header">
		<h1>Welcome to the Gaming Landing Page</h1>
	</div>

	<div class="nav">
		<ul>
			<li><a href="index.php">Home</a></li>
			<li><a href="games.php">Games</a></li>
			<li><a href="contact.php">Contact</a></li>
		</ul>
	</div>

	<div class="container">
		<h2>Featured Games</h2>
		
		<?php
			$db = mysqli_connect("localhost", "root", "", "gaming");
			$sql = "SELECT * FROM games";
			$result = my
