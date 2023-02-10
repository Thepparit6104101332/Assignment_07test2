<script setup>
import{RouterLink , RouterView} from 'vue-router'


</script>

<template>

<header>
    
  <h1 style="font-size:60px;">เพิ่มถอนรายวิชา</h1>


</header>
<nav>
<ul>

  <li><RouterLink to="ประกาศข่าวสาร">ประกาศข่าวสาร</RouterLink></li>
  <li><RouterLink to="รายชื่อวิชาในแผนการเรียน">รายชื่อวิชาในแผนการเรียน</RouterLink></li>
  <li><RouterLink to="การเพิ่มถอนวิชา">การเพิ่มถอนวิชา</RouterLink></li>
  
</ul>
</nav>
<RouterView/>

</template>

<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}

h1{
    padding: 20px;
}



</style>