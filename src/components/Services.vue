<template>
  <div class="home">
    <img class="imagemHome" src="../assets/plaquinha11.jpg">
    <p class="nome"> SERVICES </p> 
    <div class="imaServices">
    <img class="imagemS" src="../assets/plaquinha6.jpg">
    <img class="imagemS1" src="../assets/plaquinha7.jpg">
    <img class="imagemS2" src="../assets/plaquinha8.jpg">
    <img class="imagemS3" src="../assets/plaquinha9.jpg">
    <img class="imagemS4" src="../assets/plaquinha10.jpg">
    </div>
    <div class="descricao">
      <p class="textServices"> A lojinea que patrocina a sua lojinea! </p>
      <p class="textServices2"> Algumas das que patrocinamos: </p>
      </div>
    </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Anton');
 
  .imagemHome {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    z-index: -1;
    height: 100%;
  }
  .nome {
    color: rgba(214, 143, 62, 0.65);
    position: absolute;
    bottom: 280px;
    right: 100px;
    font-size: 75px;
    font-family: Anton;
    text-shadow: #000000 1px 2px 2px;
    /*border: #000 1px solid;*/
    /*padding: 10px;*/
    /*background-color: rgba(0, 0, 0, 0.3);*/
  }
  .imagemS, .imagemS1, .imagemS2, .imagemS3, .imagemS4 {
    border-radius: 5px;
    width: 200px;
    position: absolute;
    bottom: 50px;
    border: 2px solid black;
    box-shadow: #000 2px 2px 1px;
  }
  .imagemS {
    left: 90px;
  }
  .imagemS1 {
    left: 350px;
  }
  .imagemS2 {
    left: 600px;
  }
  .imagemS3 {
    left: 850px;
  }
  .imagemS4 {
    left: 1100px;
  }
  .descricao {
    font-size: 40px;
    text-shadow: #000000 1px 2px 2px;
    font-family: 'Encode Sans Expanded|Shadows Into Light';
  }
  .textServices {
  }
  .textServices2 {

  }
</style>
}