<div class="header">
<img id="logo" class="cup-img" src="assets/css/Logo_&_Cup_page_1.jpg"/>
<img id="icon" class="menu-icon" onclick="showMenu(this)" src="assets/css/Menu_icon_page_1.jpg"/>
<div/>
<div class="footer">Copyright ©️ 2022-2023, Macchiato Incorporated. All Rights Reserved.<div/>
<div id="dropdown" class="menu">
   <ul class="menu-items">
      <li class="item"><a class="itemLink">MIST<a/><li/>
      <li class="item"><a class="itemLink">Security<a/><li/>
      <li class="item"><a class="itemLink">DLT<a/><li/>
      <li class="item"><a class="itemLink">Cloud<a/><li/>
      <li class="item"><a class="itemLink">Networking<a/><li/>
      <li class="item"><a class="itemLink">Connect<a/><li/>
   <ul/>
<div/>

<script>
var logo = document.getElementById("logo");
var icon = document.getElementById("icon");
var dropdown = document.getElementById("dropdown");

function showMenu(mi) {
icon.style.display = "block";
}
<script/>
