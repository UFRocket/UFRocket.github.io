---
layout: none
permalink: /rockets
---
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" type="text/css" href="rockets.css">
  <title>Rockets</title>
</head>

<!-- page header -->
<header>
  <button><a href="/">Home</a></button>
  <button><a href="/force">Force</a></button>
  <button><a href="/rockets">Rockets</a></button>
  <div class="header">
    <h3>ROCKETS</h3>
  </div>
</header>

<!-- navigation links under header -->
<nav>
  <ul>
    <li><a href="#basics">Basics |</a></li>
    <li><a href="#parts">Rocket Parts</a></li>
  </ul>
</nav>

<!-- Rocket Basics box -->
<div id="basics">
  <h2><u>Rocket Basics</u></h2>
  <p>What is a Rocket?</p>
  <p>&middot; Cylindrical object projected into the air</p>
  <p>&middot; Used for fun, exploration, and research</p>

<!-- Bottle rocket image -->
  <div class="container">
    <img src="/assets/images/rocket fun.jpg" class="image">
    <div class="hover_overlay">
      <div class="text">
        Research on how to build a bottle rocket!
      </div>
    </div>  
  </div>  

<!-- Space rocket image -->
<div class="container">
  <img src="/assets/images/rocket_exp.png" class="image">
  <div class="hover_overlay">
    <div class="text">
      Rockets can bring people to space!
    </div>
  </div>  
</div>  

<!-- Satellite image -->
<div class="container">
  <img src="/assets/images/research.jpg" class="image">
  <div class="hover_overlay">
    <div class="text">
      NASA uses rockets to launch satellites into space!
    </div>
  </div>  
</div>
</div>

<!-- Rocket image clickable parts for more info -->
<div id="parts">
  <h2><u>Rocket Parts</u></h2>
  <p>Click on a part to learn more!</p>
  <!-- Image Map Generated by http://www.image-map.net/ -->
  <img src="/assets/images/rocket.png" usemap="#image-map">

  <map name="image-map">
      <area target="" alt="nose cone" title="nose cone" href="#nose_cone" coords="113,214,146,197,168,188,188,187,197,186,195,234,198,240,183,241,162,236,145,229" shape="poly">
      <area target="" alt="nose cone label" title="nose cone" href="#nose_cone" coords="16,255,128,323" shape="rect">
      <area target="" alt="shock cord" title="shock cord" href="#shock_cord" coords="202,216,258,222,311,228,313,236,213,237" shape="poly">
      <area target="" alt="shock cord label" title="shock cord label" href="#shock_cord" coords="127,347,187,387" shape="rect">
      <area target="" alt="parachute lines label" title="parachute lines label" href="#para_lines" coords="34,94,123,136" shape="rect">
      <area target="" alt="parachute lines" title="parachute lines" href="#para_lines" coords="207,209,332,193,317,214,329,235" shape="poly">
      <area target="" alt="parachute" title="parachute" href="#parachute" coords="352,213,28" shape="circle">
      <area target="" alt="parachute label" title="parachute label" href="#parachute" coords="278,58,375,87" shape="rect">
      <area target="" alt="lug1" title="lug1" href="#launch_lug" coords="252,176,283,189" shape="rect">
      <area target="" alt="lug2" title="lug2" href="#launch_lug" coords="433,176,465,187" shape="rect">
      <area target="" alt="lug label" title="lug label" href="#launch_lug" coords="126,47,200,94" shape="rect">
      <area target="" alt="rec wadding" title="rec wadding" href="#recov_wadding" coords="396,194,418,235" shape="rect">
      <area target="" alt="rec wadding label" title="rec wadding label" href="#recov_wadding" coords="324,351,411,395" shape="rect">
      <area target="" alt="eng mount" title="eng mount" href="#eng_mount" coords="420,191,435,236" shape="rect">
      <area target="" alt="eng mount label" title="eng mount label" href="#eng_mount" coords="479,325,603,374" shape="rect">
      <area target="" alt="rocket eng" title="rocket eng" href="#rocket_eng" coords="437,194,550,232" shape="rect">
      <area target="" alt="rocket eng label" title="rocket eng label" href="#rocket_eng" coords="463,14,619,58" shape="rect">
      <area target="" alt="fin1" title="fin1" href="#fins" coords="468,184,518,128,577,131,547,186" shape="poly">
      <area target="" alt="fin2" title="fin2" href="#fins" coords="477,239,526,274,584,275,550,238" shape="poly">
      <area target="" alt="fin label" title="fin label" href="#fins" coords="622,131,680,162" shape="rect">
      <area target="" alt="body tube label" title="body tube label" href="#body_tube" coords="631,230,688,271" shape="rect">
  </map>
  </div>

<!-- Rocket Parts Content in Popup -->
<!-- nose cone -->
<div id="nose_cone" class="overlay">
	<div class="popup">
		<h2>Nose Cone Payload (Removable)</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
			<ul>
        <li>Affects the thermodynamics</li>
        <li>Reduces drag</li>
        <li>Hobbyists often choose ogive</li>
      </ul>
      <img src="/assets/images/nose cones.png" width="300">
		</div>
	</div>
</div>

<!-- shock cord -->
<div id="shock_cord" class="overlay">
	<div class="popup">
		<h2>Shock Cord</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
			content
		</div>
	</div>
</div>

<!-- parachute lines -->
<div id="para_lines" class="overlay">
	<div class="popup">
		<h2>Parachute Lines</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
      See <b>Parachute</b> for more info!
      <img src="/assets/images/parachute.png" height="300">
		</div>
	</div>
</div>

<!-- parachute -->
<div id="parachute" class="overlay">
	<div class="popup">
		<h2>Parachute</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
      <ul>
        <li>Deploys at <b><font color="green">apogee</font></b> (highest point)</li>
        <li>Slows descent of rocket for safe recovery</li>
      </ul>
      <img src="/assets/images/parachute.png" height="300">
		</div>
	</div>
</div>

<!-- launch lug -->
<div id="launch_lug" class="overlay">
	<div class="popup">
		<h2>Launch Lug</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
			content
		</div>
	</div>
</div>

<!-- recovery wadding -->
<div id="recov_wadding" class="overlay">
	<div class="popup">
		<h2>Recovery Wadding</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
			content
		</div>
	</div>
</div>

<!-- engine mount -->
<div id="eng_mount" class="overlay">
	<div class="popup">
		<h2>Engine Mount (Fixed)</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
			content
		</div>
	</div>
</div>

<!-- rocket engine -->
<div id="rocket_eng" class="overlay">
	<div class="popup">
		<h2>Rocket Engine</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
    <ul>
      <li>Motor contains fuel</li>
      - Potential energy &rarr; Kinetic energy<br>
      - Chemical reaction provides thrust<br>
      <li>Newton's Third Law</li>
    </ul>
    <img src="/assets/images/motor.png" width="200">
		</div>
	</div>
</div>


<!-- fins -->
<div id="fins" class="overlay">
	<div class="popup">
		<h2>Fins</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
      <ul>
        <li>Provides stability at the cost of more drag</li>
        <li>No set shape</li>
        <li>Symmetrically placed around rockets</li>
      </ul>
      <img src="/assets/images/fins.png" width="400">
		</div>
	</div>
</div>

<!-- body tube -->
<div id="body_tube" class="overlay">
	<div class="popup">
		<h2>Body Tube</h2>
		<a class="close" href="#parts">&times;</a>
		<div class="content">
      <ul>
        <li>Structural component of rocket</li>
        <li>Provides payload (storage) space</li>
        <li>Length and diameter affect center of gravity and stability</li>
      </ul>
      <img src="/assets/images/body tube.png" width="400">   
		</div>
	</div>
</div>
