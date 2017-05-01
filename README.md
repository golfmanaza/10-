<html>
<title>10ร้านห้ามพลาดในหาดใหญ่</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1 {font-family: "Montserrat", sans-serif}
img {margin-bottom: -7px}
.w3-row-padding img {margin-bottom: 12px}

</style>
<body>

<!-- Sidenav -->

<!-- !PAGE CONTENT! -->
<div class="w3-content" style="max-width:1500px">

<!-- Header -->
<header class="w3-container w3-padding-32 w3-center w3-opacity w3-margin-bottom">
  <span class="w3-opennav w3-xxlarge w3-right w3-margin-right" onclick="w3_open()"></i></span> 
  <div class="w3-clear"></div>
  <h1><b>10ร้านห้ามพลาดในหาดใหญ่</b></h1>
  <p><b>Pictures by Thitima,Fatin and kritsada.</b></p>
  <p class="w3-padding-16"><button class="w3-button w3-black" onclick="myFunction()">Toggle Grid Padding</button></p>
</header>

<!-- Photo Grid -->
<div class="w3-row" id="myGrid" style="margin-bottom:128px">
  <div class="w3-third">
    <img src="kiriko.jpg" style="width:100%">
    <img src="korkai.jpg" style="width:100%">
    <img src="suanloungjerm.jpg" style="width:100%">
    <img src="three.jpg" style="width:100%">
    
  </div>

  <div class="w3-third">
    <img src="krarok.jpg" style="width:100%">
    <img src="mrsteak.jpg" style="width:100%">
    <img src="thongwong.jpg" style="width:100%">
   
  </div>

  <div class="w3-third">
    <img src="naichang.jpg" style="width:100%">
    <img src="soulbbq11.jpg" style="width:100%">
    <img src="forseen.jpg" style="width:100%">
    
  </div>
</div>

<!-- End Page Content -->
</div>

<!-- Footer -->

<script>
// Toggle grid padding
function myFunction() {
    var x = document.getElementById("myGrid");
    if (x.className === "w3-row") {
        x.className = "w3-row-padding";
    } else { 
        x.className = x.className.replace("w3-row-padding", "w3-row");
    }
}

// Open and close sidenav
function w3_open() {
    document.getElementById("mySidenav").style.width = "100%";
    document.getElementById("mySidenav").style.display = "block";
}

function w3_close() {
    document.getElementById("mySidenav").style.display = "none";
}
</script>

</body>
</html>
