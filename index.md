---
layout: default
---
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">

<style>
.dropbtn {
  background-color: #555;
  color: white;
  width: 600px;  
  padding: 12px;
  font-size: 16px;
  border: none;
  cursor: pointer;
}

.dropdown {
  position: relative;
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
}

.dropdown-content a:hover {background-color: #f1f1f1}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown:hover .dropbtn {
  background-color: #3e8e41;
}
</style>


<div id="title">
  <img src="images/humanaLogo2.png">
 <br>
  <h1><em><center>IHWA Analysis</center></em></h1>          
</div>

<div class="dropdown">
  <button class="dropbtn">Menu</button>
  <div class="dropdown-content">
  <a href="section1">Tye of Plan & Membership by Medicare Region</a>
  <a href="section2">IHWA by Medicare Region</a>
  <a href="section3">IHWA by Sociodemographic</a>
</div>
</div>

<br>
 <br>
  <p>[Add intro (and takeaways?) here]</p>
 <br>
 <br>
 <br>
 <br>
  
  
<div class="main" id="section1">
<h2><small>Plan and Membership Type by Medicare Region</small></h2>
    
<div class="row">
  <div class="column">
    <h3><b><i><small>Type of membership</small></i></b></h3>
   <iframe src="maps/MembershipType.html" height=260 width=300></iframe>
  </div>
  <div class="column">
    <h3><b><i><small>Type of plan</small></i></b></h3>
       <iframe src="maps/PlanType.html" height=260 width=300></iframe>
  </div>
</div>

<div class="row">
  <div class="column">
    <h3><b><i><small>IHAP levels</small></i></b></h3>
   <iframe src="maps/IHAPlevel.html" height=260 width=300></iframe>
  </div>
  <div class="column">
 <br>
 <br>

    <p>[Add interpretation here]</p>
  </div>
</div>
</div>
 <br>
 <br>
 <br>
 <br>

<div class="main" id="section2">
<h2><small>IHWA by Medicare Region</small></h2>

<div class="row">
  <div class="column">
    <h3><b><i><small>Type of membership</small></i></b></h3>
   <iframe src="maps/MembershipType.html" height=260 width=300></iframe>
  </div>
  <div class="column">
    <h3><b><i><small>Type of plan</small></i></b></h3>
       <iframe src="maps/PlanType.html" height=260 width=300></iframe>
  </div>
</div>
  <div class="row">
  <div class="column">
    <h3><b><i><small>Type of membership</small></i></b></h3>
   <iframe src="maps/MembershipType.html" height=260 width=300></iframe>
  </div>
  <div class="column">
    <h3><b><i><small>Type of plan</small></i></b></h3>
       <iframe src="maps/PlanType.html" height=260 width=300></iframe>
  </div>
</div>
</div>

 <br>
 <br>
 <br>
 <br>


<div class="main" id="section3">
<h2><small>IHWA by Sociodemographic</small></h2>
    <h3><b><i><small>Correlation between IHWA indicators and the proportion of population from each racial group at each zip code</small></i></b></h3>
   <iframe src="charts/IHWA_race.jpg" height=400 width=600 ></iframe>
    <h3><b><i><small>IHWA indicators per socioeconomic class at each zip code</small></i></b></h3>
   <iframe src="charts/IHWA_income.jpg" height=400 width=600 ></iframe>

  
 </div>
