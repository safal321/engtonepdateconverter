# engtonepdateconverter
A laravel package that converts english date to nepali date


<!DOCTYPE html>
<html>
<head>
	<style>
	p{
	color:red;
	}
	</style>
</head>
<body>
<h1>A laravel package that converts english date to nepali date.</h1>
<p>Instructions:</p>
<p> 1) Run composer require safal/engtonepdateconverter</p>
<p> 2) Or add "safal/engtonepdateconverter": "^1.0" in composer.json and run composer update</p>
<p> 3) And that's it ,no need to add service provider as it is auto loaded. </p>

<h3>Usage</h3>
To convert english date to nepali date,<br>
use the NepaliDate Facade as:<br>
<p>NepaliDate::convertToNepaliDate(2019,01,13);</p>
Output: २०७५/९/२९


</body>
</html>
