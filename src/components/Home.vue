<template>
  <div class="home">
    <img class="imagemHome" src="../assets/plaquinha.jpg">
    <div class="texto1">
      <p> Welcome to </p>
    </div>
      <div class="texto2">
      <p> Welcome to </p>
    </div>
    <div class="texto3">
      <p> Duda's shop </p>
    </div>
    <div class="texto4">
      <p> Duda's shop </p>
    </div>
    <div class="texto5">
      <p> Lojinea que ajuda a sua lojinea a crescer </p>
    </div>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Anton');
  @import url('https://fonts.googleapis.com/css?family=Titillium+Web');
  @import url('https://fonts.googleapis.com/css?family=Lobster');
  .imagemHome {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    z-index: -1;
    height: 100%;
  }
   /*.bolota {
    position: absolute;
    bottom: 30px;
    right: 40px;
    border: 3px solid yellow;
    border-radius: 50%;
    width: 250px;
    height: 250px;
    opacity: 0.2;
  }*/
  .texto1  {
    color: yellow;
    position: absolute;
    bottom: 120px;
    right: 70px;
    font-size: 60px;
    font-family: Anton;
    opacity: 0.3;
    font-weight: bold;

  }
  .texto2  {
    color: white;
    position: absolute;
    bottom: 120px;
    right: 70px;
    font-size: 60px;
    font-family: Anton;
    opacity: 0.3;
    font-weight: bold;

  }
  .texto3  {
    color: yellow;
    position: absolute;
    bottom: 30px;
    right: 70px;
    font-size: 80px;
    font-family: Lobster;
    opacity: 0.3;
    font-weight: bold;
    text-shadow: #999 1px 2px 2px

  }
  .texto4  {
    color: yellow;
    position: absolute;
    bottom: 30px;
    right: 70px;
    font-size: 80px;
    font-family: Lobster;
    opacity: 0.3;
    font-weight: bold;
    text-shadow: #999 1px 2px 2px

  }
  .texto5  {
    color: white;
    position: absolute;
    bottom: 72px;
    right: 70px;
    font-size: 15px;
    font-family: Titillium Web;
    opacity: 0.8;

  }
</style>
