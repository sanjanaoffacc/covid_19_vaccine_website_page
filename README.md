# covid_19_vaccine_website_page
<!DOCTYPE html>
<html>
<head>

<title>mygov.in/covid-19</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
/* Style the body */
body {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;
}

/* Header/logo Title */
.header {
  padding: 80px;
  text-align: center;
  background: #1abc9c;
  color: white;
}

/* Increase the font size of the heading */
.header h1 {
  font-size: 40px;
}
* {box-sizing: border-box}

/* Set height of body and the document to 100% */
body, html {
  height: 100%;
  margin: 0;
  font-family: Arial;
}

/* Style tab links */
.tablink {
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink:hover {
  background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: black;
  display: none;
  padding: 100px 20px;
  height: 100%;
}
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

/* The grid: Four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 10px;
}

/* Style the images inside the grid */
.column img {
  opacity: 0.8; 
  cursor: pointer; 
}

.column img:hover {
  opacity: 1;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The expanding image container */
.container {
  position: relative;
  display: none;
}

/* Expanding image text */
#imgtext {
  position: absolute;
  bottom: 15px;
  left: 15px;
  color: white;
  font-size: 20px;
}

/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10px;
  right: 15px;
  color: white;
  font-size: 35px;
  cursor: pointer;
}

#Home {background-color: ghostwhite;}
#News {background-color: ghostwhite;}
#Contact {background-color: ghostwhite;}
#About {background-color: ghostwhite;}
</style>
</head>
<body>
<body style="background-color:powderblue;">

</body>
<div class="header">
  <h1>COVID-19 HELPDESK</h1>
  <p><b>#INDIA FIGHTS BACK CORONA</b></p>
</div>

<button class="tablink" onclick="openPage('Home', this, 'chocolate')">Covid-19 symptoms</button>
<button class="tablink" onclick="openPage('News', this, 'chocolate')" id="defaultOpen">Post-Covid Care</button>
<button class="tablink" onclick="openPage('Contact', this, 'chocolate')">Covid vaccination
</button>
<button class="tablink" onclick="openPage('About', this, 'chocolate')">FAQ'S
</button>


<div id="Home" class="tabcontent">
  <p>COVID-19 affects different people in different ways. Most infected people will develop mild to moderate illness and recover without hospitalization.
Most common symptoms:
<ul>
  <li>fever</li>
  <li>dry cough</li>
  <li>tiredness</li>
</ul>
<p>                   </p>
Less common symptoms:
<li>aches and pains</li>
<li>sore throat</li>
<li>diarrhoea</li>
<li>conjunctivitis</li>
<li>headache</li>
<li>loss of taste or smell</li>
<li>a rash on skin, or discolouration of fingers or toes</li>
<p>                   </p>
Serious symptoms:
<li>difficulty breathing or shortness of breath</li>
<li>chest pain or pressure</li>
<li>loss of speech or movement</li>
<p>                   </p>
Seek immediate medical attention if you have serious symptoms. Always call before visiting your doctor or health facility.
People with mild symptoms who are otherwise healthy should manage their symptoms at home.
On average it takes 5–6 days from when someone is infected with the virus for symptoms to show, however it can take up to 14 days.
For informational purposes only. Consult your local medical authority for advice.</p>
</div>


<div id="News" class="tabcontent">
  <div class="column">
    GUIDELINESSSSSSSSSSSSSSSSSSSS
  </div> 
</div>

<div id="Contact" class="tabcontent">
  <head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

/* The grid: Four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 10px;
}

/* Style the images inside the grid */
.column img {
  opacity: 0.8; 
  cursor: pointer; 
}

.column img:hover {
  opacity: 1;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The expanding image container */
.container {
  position: relative;
  display: none;
}

/* Expanding image text */
#imgtext {
  position: absolute;
  bottom: 15px;
  left: 15px;
  color: white;
  font-size: 20px;
}

/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10px;
  right: 15px;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
</style>
</head>
<body>



<!-- The four columns -->
<div class="row">
  <div class="column">
    <a href="closure_1.html">
<img src="IMAGE_1.jpg" alt="HTML tutorial" style="width:390px;height:400px;">
</a>
  </div>
  
  <div class="column">
    <a href="closure_1.html">
<img src="IMAGE_4.jpg" alt="HTML tutorial" style="width:390px;height:400px;">
</a>
  </div>
  <div class="column">
    <a href="closure_1.html">
<img src="IMAGE_5.jpg" alt="HTML tutorial" style="width:390px;height:400px;">
</a>
  </div>
  <div class="column">
    <a href="closure_1.html">
<img src="IMAGE_6.jpg" alt="HTML tutorial" style="width:390px;height:400px;">
</a>
  </div>
</div>

<div class="container">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <img id="expandedImg" style="width:100%">
  <div id="imgtext"></div>
</div>

<script>
function myFunction(imgs) {
  var expandImg = document.getElementById("expandedImg");
  var imgText = document.getElementById("imgtext");
  expandImg.src = imgs.src;
  imgText.innerHTML = imgs.alt;
  expandImg.parentElement.style.display = "block";
}
</script>

</body>
</div>

<div id="About" class="tabcontent">
  <h3>About</h3>
  <p>Who we are and what we do.</p>
</div>

<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> 
#code of second page
<!DOCTYPE html>
<html>
<head>
<title>mygov.in/covid-19/mobile number registration </title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
form {border: 3px solid #f1f1f1;}

input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

button {
  background-color: #04AA6D;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}

button:hover {
  opacity: 0.8;
}

.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}

.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}

img.avatar {
  width: 20%;
  border-radius: 50%;
}

.container {
  padding: 16px;
}

span.psw {
  float: right;
  padding-top: 16px;
}

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
  span.psw {
     display: block;
     float: none;
  }
  .cancelbtn {
     width: 100%;
  }
}
</style>
</head>
<body>

<h2>Login Form</h2>

<form action="/action_page.php" method="post">
  <div class="imgcontainer">
    <img src="image_2.jpg" alt="Avatar" class="avatar">
	<p>An OTP will be send to your mobile number</p>
  </div>

  <div class="container">
    <label for="uname"><b>Mobile number</b></label><b></br>
	<input type="text" id="username" name="username" required>
    <label for="psw"><b>Enter the 6-digit OTP</b></label>
    <input type="password" placeholder="Enter the OTP" name="psw" required>
	<div class="column">

  </div>

  <input type=button onClick="location.href='closure_2.html'"
 value='click here'>
 
  </div>
</form>

</body>
</html>
#code of 3rd page

