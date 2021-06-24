---
layout: splash
classes: wide
permalink: /search/
---

<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="utf-8">
    <link id="u-page-google-font" rel="stylesheet" href="https://fonts.googleapis.com/css?family=Abril+Fatface:400">
    


<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
	
<link href="/CatalogoFEMP/stylesheet.css" rel="stylesheet"/>
	
	    
 <div class="navMenu">   
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="https://opencitydata.github.io/CatalogoFEMP/" style="text-decoration: none;">Catalogue</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarResponsive">
    <ul class="navbar-nav mr-auto">

      <li class="nav-item">
        <a class="nav-link" href="https://github.com/opencitydata/" style="text-decoration: none;">Open City GitHub</a>
      </li>
	    
	<li class="nav-item">
        <a class="nav-link" href="http://vocab.linkeddata.es/datosabiertos/" style="text-decoration: none;">Open Data Cities</a>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="/CatalogoFEMP/contact/" style="text-decoration: none;">Contact</a>
      </li>
      
    </ul>
  </div>
</nav>
<br><br>
</div>
	  
  </head>
	
		
  <body class="bodyc" style="font-size: 16px;">
	
	  <div class="container">
		
		 <div class="row">	   
			 <div class="col-md">
			 <h2> Search </h2>
			 </div>
		  </div>
		  
		 
		   <div class="row">			   
			 <div class="col-md">
			   	<input type="text" id="search" onkeyup="myFunction()" placeholder="Search for names.." title="Type in a name">

				<ul id="names">
				  <li><a href="#">Adele</a></li>
				  <li><a href="#">Agnes</a></li>

				  <li><a href="#">Billy</a></li>
				  <li><a href="#">Bob</a></li>

				  <li><a href="#">Calvin</a></li>
				  <li><a href="#">Christina</a></li>
				  <li><a href="#">Cindy</a></li>
				</ul>
				 
			   </div>
		  </div>
		  
		  
	  </div>  
	  
	  <script>
function myFunction() {
    var input, filter, ul, li, a, i, txtValue;
    input = document.getElementById("search");
    filter = input.value.toUpperCase();
    ul = document.getElementById("names");
    li = ul.getElementsByTagName("li");
    for (i = 0; i < li.length; i++) {
        a = li[i].getElementsByTagName("a")[0];
        txtValue = a.textContent || a.innerText;
        if (txtValue.toUpperCase().indexOf(filter) > -1) {
            li[i].style.display = "";
        } else {
            li[i].style.display = "none";
        }
    }
}
</script>
		  
	  
    
  </body>
</html>




