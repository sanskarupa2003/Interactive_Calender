<DOCTYPE HTML!>
<html>
<head>

<h1>
EVENT CALENDAR
</h1>

<style>

h1 {
  font-family: "Times New Roman", Times, serif;
  color: #;
  font-size: 50px
}




body {
  background-image: url('white.jpg');
  background-repeat: no-repeat;
  background-size: cover;  
}


ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color:#FF9800;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
</style>

<link href="css.css" rel="stylesheet">
<script async src="script.js"></script>

</head>

<body>
<ul>
  <li><a class="active" href="project.html">Home</a></li>
  
  <li><a href="aboutus.html">About Us</a></li>
</ul>

 <div id="cal-wrap">
      <!-- FOR CHOOSING YEAR MONTH -->
      <div id="cal-date">
        <select id="cal-mth"></select>
        <select id="cal-yr"></select>
      </div>

      <!-- CALENDAR -->
      <div id="cal-container"></div>

      <!--EVENT FORM -->
      <form id="cal-event">
        <h1 id="evt-head"></h1>
        <div id="evt-date"></div>
        <textarea id="evt-details" required></textarea>
        <input id="evt-close" type="button" value="Close"/>
        <input id="evt-del" type="button" value="Delete"/>
        <input id="evt-save" type="submit" value="Save"/>
      </form>
    </div>

</body>
</html>
