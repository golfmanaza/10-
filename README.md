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
<nav class="w3-sidenav w3-black w3-animate-top w3-center w3-xxlarge" style="display:none;padding-top:150px" id="mySidenav">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-closenav w3-jumbo w3-display-topright" style="padding:6px 24px">
    <i class="fa fa-remove"></i>
  </a>
</nav>

<!-- !PAGE CONTENT! -->
<div class="w3-content" style="max-width:1500px">

<!-- Header -->
<header class="w3-container w3-padding-32 w3-center w3-opacity w3-margin-bottom">
  <div class="w3-clear"></div>
  <h1><b>10ร้านห้ามพลาดในหาดใหญ่</b></h1>
  <p><b>Food Pictures by Thitima,Fatin and Kritsada.</b></p>
  <p class="w3-padding-16"><button class="w3-button w3-black" onclick="myFunction()">Toggle Grid Padding</button></p>
</header>

<!-- Photo Grid -->
<div class="w3-row" id="myGrid" style="margin-bottom:128px">
  <div class="w3-third">
   <a href="https://golfmanaza.github.io/Kiriko-Japannese-Food/"><img src="kiriko.jpg" style="width:100%"></a>        
    <a href="https://golfmanaza.github.io/KorKai/"><img src="korkai.jpg" style="width:100%"></a>    
    <a href="https://golfmanaza.github.io/Suan-loung-jerm/"><img src="suanloungjerm.jpg" style="width:100%"></a>   
    <img src="three.jpg" style="width:100%">
    
  </div>

  <div class="w3-third">
       <a href="https://golfmanaza.github.io/somtamKrarok/"><img src="krarok.jpg" style="width:100%"></a>  
       <a href="https://golfmanaza.github.io/MR.STEAK/"><img src="mrsteak.jpg" style="width:100%"></a>
       <a href="https://golfmanaza.github.io/Thongwong/"><img src="thongwong.jpg" style="width:100%"></a>
          
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
<footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin-top:128px"> 
  <i class="fa fa-facebook-official w3-hover-text-indigo"></i>
   <i class="fa fa-instagram w3-hover-text-purple"></i>
  
</footer>
 
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
