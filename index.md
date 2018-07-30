<link rel="stylesheet" type="text/css" href="index.css">
<header id="luxbar" classNameN="luxbar-fixed">
    <div className="luxbar-menu luxbar-menu-right luxbar-menu-material-cyan">
        <ul className="luxbar-navigation">
          <h1>Menu</h1>
            <li className="luxbar-header">
                <label className="luxbar-hamburger luxbar-hamburger-doublespin"
                id="luxbar-hamburger" for="luxbar-checkbox"> <span></span> </label>
            </li>
        </ul>
    </div>
</header>
<br>

<a href="aboutme.html">About me</a>
<a href="me&it.html">Me&IT</a>
<a href="mypassion.html">My passion</a>
<a href="siteborn.html">Birth of site</a>

<meta http-equiv="X-UA-Compatible" content="IE=edge">
## Welcome
The site is under development.
I am trying to make it look like a normal site, but it will take a lot of time.

<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li a, .dropbtn {
    display: inline-block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover, .dropdown:hover .dropbtn {
    background-color: red;
}

li.dropdown {
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}

.dropdown-content a:hover {background-color: #f1f1f1}

.dropdown:hover .dropdown-content {
    display: block;
}
</style>
</head>
<body>

<ul>
  <li><a href="#home">Home</a></li>
  <li><a href="#news">News</a></li>
  <li class="dropdown">
    <a href="javascript:void(0)" class="dropbtn">Dropdown</a>
    <div class="dropdown-content">
      <a href="#">Link 1</a>
      <a href="#">Link 2</a>
      <a href="#">Link 3</a>
    </div>
  </li>
</ul>

<h3>Dropdown Menu inside a Navigation Bar</h3>
<p>Hover over the "Dropdown" link to see the dropdown menu.</p>
