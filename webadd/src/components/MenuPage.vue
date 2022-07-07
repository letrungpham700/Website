<template>
  <div id="menu">
    <body>
      <div class="topnav">
        <a class="menupage" href="MenuPage.vue">
          <img class="logo" src="../assets/mwg.png" alt="LogoThegioididong">
        </a>
        <a href="info">InfoUser</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
      </div>
    </body>

    <h1>Menu</h1>
    <h2>Zabbix</h2>
    <div>
      <div class="choice"><a href="AddHost.vue">Add Host Zabbix!</a></div>
      <div class="choice"><a href="AddHost.vue">Delete Host Zabbix!</a></div>
    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style scoped>

a {
  text-decoration: none;
}
img{
  float:initial; width:50px; height:30px;
}
body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

.topnav {
  overflow: hidden;
  background-color: #feae36;
}

.topnav a {
  float: left;
  color: black;
  text-align: center;
  padding: 15px 25px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: rgb(255, 255, 255);
  color: black;
}

.topnav a.active {
  background-color: #04AA6D;
  color: black;
}
h1{
  color: #000;
}
h2{
  border: 2px solid black;
  background-color: white;
  border-color: #f44336;
  color: red;
  padding: 14px 28px;
  font-size: 20px;
  cursor: pointer;
}
.choice a{
  background-color: #ddd;
  border: none;
  color: black;
  padding: 10px 30px;
  text-align: center;
  font-size: 20px;
  margin: 4px 2px;
  transition: 0.3s;
  float: left;
  border-radius: 20px;
  box-shadow: 0 9px #999;
}
.choice:hover a{
  background-color: #1a801e;
  color: white;
}
.choice:active a{
  background-color: #05d212;
  box-shadow: 0 5px #666;
  transform: translateY(4px);
}
</style>