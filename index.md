---
layout: default
---

<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">

<div id="title">
  <img src="images/humanaLogo2.png">
 <br>
  <h1><em><center>IHWA Analysis</center></em></h1>          
</div>

  
<div class="navbar">  
<div class="dropdown">
  <button class="dropbtn">Menu
   <i class="fa fa-caret-down"></i>
    </button>
  <div class="dropdown-content">
<ul id="nav">    
  <li><a href="#section1">Tye of Coverage & Eligibility by Medicare Region</a></li>
  <li><a href="#section2_all">IHWA by Medicare Region</a>   
  <ul>
      <li><a href="#section2_all">All Members</a></li>
      <li><a href="#section2_plan">By Type of Coverage</a></li>
      <li><a href="#section2_eligibility">By Type of Plan</a></li>    
  </ul>  
  </li>   
  <li><a href="#section3">IHWA by Sociodemographic</a></li>
</ul>
</div>
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
<h2><small>Type of Coverage and Eligibility by Medicare Region</small></h2>
    
<div class="row">
  <div class="column">
    <h3><b><i><small>Eligibility</small></i></b></h3>
   <iframe src="maps/MembershipType_fullDataset.html" height=260 width=300></iframe>
  </div>
  <div class="column">
    <h3><b><i><small>Type of Coverage</small></i></b></h3>
       <iframe src="maps/PlanType_fullDataset.html" height=260 width=300></iframe>
  </div>
</div>

<div class="row">
  <div class="column">
    <h3><b><i><small>IHAP Levels</small></i></b></h3>
   <iframe src="maps/IHAPlevel_fullDataset.html" height=260 width=300></iframe>
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
 
<div class="main" id="section2_all">
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
   <p align="center"><iframe src="charts/IHWA_race.jpg" height=360 width=446></iframe></p>
    <h3><b><i><small>IHWA indicators per socioeconomic class at each zip code</small></i></b></h3>
   <p align="center"><iframe src="charts/IHWA_income.jpg" height=360 width=446 ></iframe></p>

  
 </div>

