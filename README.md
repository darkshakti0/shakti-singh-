
<!DOCTYPE html>
<html>
<head>
	<title></title>
	<style>
		.dropdown
		{
			display: inline-block;
			position: relative;
		}
		.dropbutton
		{
			padding: 10px;
		}
		.dropcontent
		{
			position: absolute;
			background-color: Cornsilk;
			width: 200px;
			display: none;
			
		}
		.dropdown:hover .dropcontent
		{
			display: block;
		}
		a
		{
			display: block;
			padding: 10px;
			text-decoration: none;
			color: black;

		}
		a:hover
		{
			background-color: black;
			color: white;
		}
	</style>
</head>
<body>
<div class="dropdown">
	<div class="dropbutton">Home</div>
</div>

<div class="dropdown">
	<div class="dropbutton">Examination</div>
	<div class="dropcontent">
		<a href="">Result</a>
		<a href="">Re-Exam</a>
		<a href="">Registration</a>
		<a href="">Exam Fees</a>
	</div>
</div>

	<div class="dropdown">
	<div class="dropbutton">Downloads</div>
	<div class="dropcontent">
		<a href="">Notes</a>
		<a href="">Books</a>
		<a href="">PDF</a>
		<a href="">Syllabus</a>
		
	</div>

</body>
</html>
