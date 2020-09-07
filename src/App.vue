<template>
  <div>
    <br />
    <div class="ui container headerTable" style = "background-color: #132f4b; padding-left: 20px; border-radius: 10px 10px 2px 2px">
      <h1 class="ui header mainTitle" style="color: white; float: middle; padding-top: 5px">
        IEEE Scheduler <span style="color: gray; font-size: 0.6em">for Bilkent</span>
      </h1>
      <div class="ui secondary pointing menu" >
        <a class="item itemH" href = "https://ieee.bilkent.edu.tr" style = "color: white">
          <i class="icon home"></i>
          Home
        </a>
        <router-link class="item itemH" to="/schedule" active-class="active" style = "color: white">
          <i class="icon calendar alternate outline"></i>
          Plan
        </router-link>
        <router-link class="item itemH" to="/courses" active-class="active" style = "color: white">
          <i class="icon university"></i>
          Courses
        </router-link>
        <router-link class="item itemH" to="/about" active-class="active" style = "color: white">
          <i class="icon info"></i>
          About
        </router-link>
      </div>
    </div>
    <br />
    <router-view/>
  </div>
</template>

<style>
  @import '/scheduleC.css';
</style>
