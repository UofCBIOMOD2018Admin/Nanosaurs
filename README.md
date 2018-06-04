<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
* {
    box-sizing: border-box;
}

body {
    margin: 0;
}

.navbar {
    overflow: hidden;
    background-color: #111;
    font-family: Arial, Helvetica, sans-serif;
}

.navbar a {
    float: left;
    font-size: 16px;
    color: lime;
    text-align: center;
    padding: 14px 32px;
    text-decoration: none;
}

.dropdown {
    float: left;
    overflow: hidden;
}

.dropdown .dropbtn {
    font-size: 32px;    
    border: none;
    outline: none;
    color: lime;
    padding: 14px 30px;
    background-color: navy;
    font: inherit;
    margin: 0;
}

.navbar a:hover, .dropdown:hover .dropbtn {
    background-color: navy;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: 111;
    width: 100%;
    left: 0;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content .header {
    background: lime;
    padding: 0px;
    color: lime;
}

.dropdown:hover .dropdown-content {
    display: block;
}

/* Create three equal columns that floats next to each other */
.column {
    float: left;
    width: 33.33%;
    padding: 10px;
    background-color: #111;
    height: 75px;
}

.column a {
    float: none;
    color: lime;
    padding: 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.column a:hover {
    background-color: navy;
}

/* Clear floats after the columns */
.row:after {
    content: "";
    display: table;
    clear: both;
}
</style>
</head>
<body>

<div class="navbar">
  <a href="#home">Home</a>
  <a href="#news">Design</a>
  <a href="#news">Lab Book</a>
  <a href="#news">Results</a>
  <div class="dropdown">
    <button class="dropbtn">About
      <i class="fa fa-caret-down"></i>
    </button>
    <div class="dropdown-content">
      <div class="header">
      </div>   
      <div class="row">
        <div class="column">
          <a href="#">Team</a>
        </div>
        <div class="column">
          <a href="#">Sponsors</a>
             </div>
          <div class="column">
          <a href="#">Special Thanks</a>
        </div>
        </div>
      </div>
    </div>
  </div> 
</div>

<div style="padding:24px">
  <h3>Mega Menu (Full-width dropdown in navbar)</h3>
  <p>Hover over the "Dropdown" link to see the mega menu.</p>
</div>

</body>
</html>
