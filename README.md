<!DOCTYPE html>
<html>
<head>
<title>Future The Barber Services</title>
<link rel="stylesheet" href="style.css">

<script src="https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js"></script>
<script src="https://www.gstatic.com/firebasejs/10.7.1/firebase-firestore.js"></script>

</head>

<body>

<div class="container">

<h1>Future The Barber</h1>
<p>We Come To You</p>

<div class="price">

<h2>Price List</h2>

<p>Normal Cut — $20</p>
<p>Cut and Dye — $25</p>
<p>Cut, Dye and Wash — $30</p>
<p>Line Up and Dye — $15</p>

</div>

<h2>Book Service</h2>

<input id="name" placeholder="Name">

<input id="contact" placeholder="Contact Number">

<select id="service">
<option>Normal Cut - $20</option>
<option>Cut and Dye - $25</option>
<option>Cut, Dye and Wash - $30</option>
<option>Line Up and Dye - $15</option>
</select>

<textarea id="description" placeholder="Description (optional)"></textarea>

<button onclick="book()">Book Now</button>

<h2>Current Queue</h2>

<ul id="queue"></ul>

</div>

<script src="script.js"></script>

</body>
</html>
