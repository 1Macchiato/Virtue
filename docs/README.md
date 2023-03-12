<div class="header">
<img id="logo" class="cup-img" src="assets/css/Logo_&_Cup_page_1.jpg"/>
<img id="icon" class="menu-icon" src="assets/css/Menu_icon_page_1.jpg"/>
<div/>

<div id="intro" class="wp">
  <h2 class="wp-heading">Introducing MIST<h2/>
  <p>
    The Macchiato Incorporated Software Toolset [MIST]
is a multi-layered framework which empowers it's userbase
with innovative and modernized technologies built to drive
the networks of the future.
  <p/>
<div/>

<div id="security" class="wp">
  <h2 class="wp-heading">Security<h2/>
  <p>
    Built in security and verification protocols ensure
all user information is securely managed using the strongest
encryption algorithms available while also giving users full control
of their data to share with whom they see fit.
  <p/>
<div/>

<div class="footer">Copyright ©️ 2022-2023, Macchiato Incorporated. All Rights Reserved.<div/>
<div id="dropdown" class="menu" onmouseout="hideMenu(this)">
   <ul class="menu-items">
      <li class="item"><a class="itemLink" onclick="hideMenu(this)">MIST<a/><li/>
      <li class="item"><a class="itemLink" onclick="hideMenu(this)">Security<a/><li/>
      <li class="item"><a class="itemLink" onclick="hideMenu(this)">DLT<a/><li/>
      <li class="item"><a class="itemLink" onclick="hideMenu(this)">Cloud<a/><li/>
      <li class="item"><a class="itemLink" onclick="hideMenu(this)">Networking<a/><li/>
      <li class="item"><a class="itemLink" onclick="hideMenu(this)">Connect<a/><li/>
   <ul/>
<div/>

<script>
var logo = document.getElementById("logo");
var icon = document.getElementById("icon");
var dropdown = document.getElementById("dropdown");
var links = document.getElementsByClassName("itemLink");

icon.onclick = function() {
dropdown.style.display = "block";
}


function hideMenu(mi) {
dropdown.style.display = "none";
}
</script>
