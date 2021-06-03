---
layout: splash
classes: wide
permalink: /contact/
---
<head>
<link href="/CatalogoFEMP/stylesheet.css" rel="stylesheet"/>
  
  <nav class="style-4">
<ul class="menu-4">
	<li class="current"><a href="https://opencitydata.github.io/CatalogoFEMP/" data-hover="Catálogo">Catálogo</a></li>
	<li class="left"><a href="http://vocab.linkeddata.es/datosabiertos/" data-hover="Open Data Cities">Open Data Cities</a></li>
	<li class="left"><a href="https://github.com/opencitydata/" data-hover="Open City GitHub">Open City GitHub</a></li>
</ul>
	</nav>
	<br><br>
  
</head>
<body>

	<form
  action="https://formspree.io/f/xbjqoqwj"
  method="POST"
>
  <label>
    Your email:
    <input type="email" name="_replyto">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>

  <!-- your other form fields go here -->

  <button type="submit">Send</button>
</form>
	
	
	
<h3>Contact Form</h3>

<div class="container">
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="country">Country</label>
    <select id="country" name="country">
      <option value="australia">Australia</option>
      <option value="canada">Canada</option>
      <option value="usa">USA</option>
    </select>

    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>

    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>
