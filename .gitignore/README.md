<!DOCTYPE html>



<html>

<head>
<title> Choosing Commodity </title>
<head><i>Please choose the commodity you want to get data for</i></head>
<br>
<link rel="stylesheet" href="Choosing Commodity.css">
</head>
<body>

<div class="outdiv">
<button class="btn">Available Options</button>
<div class="innerdiv" id="droplist">
<a href="#">Link1</a>
<a href="#">Link2</a>
<a href="#">Link3</a>
<a href="#">Link4</a>
</div>

</div>



</body>
</html>


table{
	background-color:black;
	margin-left:50px;
	margin-top:50px;
	}
	
td{
	background-color:gray;
	font-family:Arial;
	padding:15px;
}

.bld{
     font-weight:bold;
	}

<!DOCTYPE html>



<html>

<head>
<title> Data Check </title>
<link rel="stylesheet" href="ShowTable.css">
</head>
<body>

<table> 
<caption style="padding-bottom:10px;"><i><b> This is XYZ's prices for last months </b></i></caption>
<tr class="bld"> 
<td>Column1</td>
<td>Column2</td>
<td>Column3</td>
<td>Column4</td>
</tr>

<tr> 
<td>Hello4</td>
<td>Hello5</td>
<td>Hello6</td>
<td>Hello3</td>
</tr>
<tr> 
<td>Hello7</td>
<td>Hello8</td>
<td>Hello9</td>
<td>Hello3</td>
</tr>
<tr> 
<td>Hello10</td>
<td>Hello11</td>
<td>Hello12</td>
<td>Hello3</td>
</tr>

</table

</body>
</html>
.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f1f1f1;
    min-width: 160px;
    overflow: auto;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.outdiv {
    background-color: black;
    color: white;
    padding: 16px;
    font-size: 16px;
    border: none;
    cursor: pointer;
}

.outdiv:hover, .outdiv:focus {
    background-color: #2980B9;
}

.dropdown {
    position: relative;
    display: inline-block;
}


.show{
	display:block;
}

********************************************
2nd way

*****************************

<!DOCTYPE html>



<html>

<head>
<title> Choosing Commodity </title>
<link rel="stylesheet" href="2wc.css">
</head>
<body>


<h1><i>Please choose the commodity you want to get data for</i></h1>
<div id="container">
<ul>
 <li>Category1</li>
 <li>Category2</li>
 <li>Category3</li>
       <ul>
	   <li>Category3.1</li>
	   <li>Category3.2</li>
	   <li>Category3.3</li>
	   </ul>
 <li>Category4</li>
 <li>Category5</li>
</div>



</body>
</html>
#container ul{
	
	
	list-style:none;
	float:left:
	position:absolute;
	
	}
	
#container ul li{
	background-color:black;
	color:white;
	width:150px;
	padding:10px;
	border:1px solid white;
	height:30px;
	line-height:30px;
	text-align:center;
	float:left;
     position:relative;
	 display:hidden;
	
}

#container ul li.hover {
	color:green;
}

#container ul li li{
	
	
}

