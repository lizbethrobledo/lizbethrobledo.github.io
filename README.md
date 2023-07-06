# lizbethrobledo.github.io
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Add a gray background color with some padding */
body {
  font-family: Times New Roman;
  padding: 20px;
  background: #153243;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  font-size: 40px;
  text-align: center;
  background: #F4EDED;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
   background-color: white;
   padding: 20px;
   margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #F4EDED;
  margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}
</style>
</head>

<body>

<div class="header">
  <h2>IBUWJC</h2>
</div>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  margin: 0;
  font-family: Times New Roman, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: Gray;
  color: white;
}
</style>
</head>
<body>

<div class="topnav">
  <a class="active" href="#home">Home</a>
</div>

 <div class="rightcolumn">
    <div class="card">
      <h2>Our CAS Project</h2>
      <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    </div>

 <div class="rightcolumn">
    <div class="card">
      <h2>About Us</h2>
      <div class="fakeimg" style="height:100px;">Image</div>
      <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    </div>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Times New Roman;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: #F4EDED;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>
</head>
<body>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Language and Literature HL')">Language and Literature HL</button>
  <button class="tablinks" onclick="openCity(event, 'History of the Americas HL')">History of the Americas HL</button>
  <button class="tablinks" onclick="openCity(event, 'Math Y2 SL')">Math Y2 SL</button>
  <button class="tablinks" onclick="openCity(event, 'Environmental Societies and Systems SL')">Environmental Societies and Systems SL</button>
  <button class="tablinks" onclick="openCity(event, 'Biology SL')">Biology SL</button>
  <button class="tablinks" onclick="openCity(event, 'Psychology SL')">Psychology SL</button>
  <button class="tablinks" onclick="openCity(event, 'TOK & AP Govt')">TOK & AP Govt</button>
  <button class="tablinks" onclick="openCity(event, 'Spanish SL & HL')">Spanish</button>
  <button class="tablinks" onclick="openCity(event, 'German SL & HL')">Spanish</button>
</div>

<div id="Language and Literature HL" class="tabcontent">
  <h3>Language and Literature HL</h3>
  <p>Erica: </p>
  <p>Victoria: </p>
  <p>William: </p>
</div>

<div id="History of the Americas HL" class="tabcontent">
  <h3>History of the Americas HL</h3>
  <p>Erica: </p>
  <p>Victoria: </p>
  <p>William: </p>
</div>

<div id="Math Y2 SL" class="tabcontent">
  <h3>Math Y2 SL</h3>
  <p>Lizbeth: </p>
  <p>Victoria: </p>
</div>

<div id="Environmental Societies and Systems SL" class="tabcontent">
  <h3>Environmental Societies and Systems SL</h3>
  <p>Erica: </p>
  <p>Victoria: </p>
  <p>William: </p>
</div>

<div id="Biology SL" class="tabcontent">
  <h3>Biology SL</h3>
  <p>Lizbeth: </p>
  <p>Zayra: </p>
</div>

<div id="Psychology SL" class="tabcontent">
  <h3>Psychology SL</h3>
  <p>Erica: </p>
  <p>William: </p>
</div>

<div id="TOK & AP Govt" class="tabcontent">
  <h3>TOK & AP Govt</h3>
  <p>Erica: </p>
  <p>Victoria: </p>
  <p>William: </p>
</div>

<div id="Spanish SL & HL" class="tabcontent">
  <h3>Spanish SL & HL</h3>
  <p>Erica: </p>
  <p>Victoria: </p>
  <p>William: </p>
</div>

<div id="German SL & HL" class="tabcontent">
  <h3>German SL & HL</h3>
  <p>Camila: </p>
  <p>Karen: </p>
  <p>Yaneth: </p>
</div>

<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>
   
</body>

 <div class="rightcolumn">
    <div class="card">
      <h2>Contact US</h2>
      <p>You are more than welcome to email us about any question concerning IB classes, CAS Project, etc.</p>
      <p>Lizbeth: s1677565@online.houstonisd.org</p>
      <p>Erica: s1695431@online.houstonisd.org</p>
      <p>Victoria: s1812631@online.houstonisd.org</p>
      <p>William: s2191242@online.houstonisd.org</p>
    </div>
 
<div class="footer">
  <h2>Don't stress too much. You got this, we believe in you!</h2>
</div>


