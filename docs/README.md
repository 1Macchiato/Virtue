<div class="header">
<img id="logo" class="cup-img" src="assets/css/Logo_&_Cup_page_1.jpg"/>
<img id="icon" class="menu-icon" onclick="showMenu(this)" src="assets/css/Menu_icon_page_1.jpg"/>
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

function showMenu(mi) {
dropdown.style.display = "block";
}

function hideMenu(mi) {
dropdown.style.display = "none";
}
<script/>
