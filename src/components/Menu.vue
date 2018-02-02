<template>
  <div class="navbar">
    <img class="brand" src="../assets/srvc4.jpg">
    <ul class="menu">
      <li><router-link to= "/">Home</router-link></li>
      <li><router-link to= "/about">About Us</router-link></li>
      <li><router-link to= "/services">Services</router-link></li>
      <li class="ultimo-link"><router-link to= "/findUs">Find Us</router-link></li>
    </ul>
  </div>
</template>


<style>
  @import url('https://fonts.googleapis.com/css?family=Josefin+Sans|Montserrat');

  body {
    margin: 0;
    padding: 0;
  }
  .menu li { display: inline; }
  .menu li a {
    text-decoration: none;
    padding: 0 5px;
    color: white;
    border-left: 1px solid #a3a3a3;
  }
  .ultimo-link {
    border-right: 1px solid #a3a3a3;
  }
  .navbar {
    background-color: black;
    opacity: 0.65;
    padding: 10px;
    text-align: right;
    font-family: Montserrat;
    font-size: 18px;
    font-weight: bold;
  }

  .brand {
    display: inline;
    width: 120px;
    float: left;
  }
</style>
