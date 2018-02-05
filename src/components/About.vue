<template>
  <div class="about">
      <img class="imagemAbout" src="../assets/plaquinha4.jpg">   
  <div class="textoAb">
      <p> About Us</p> 
  </div>
  <div class="cabecalho">
      <p> Lorem ipsum dolor sit amet, </p>
  </div>
  <div class= "descricao"> <p> et elit integer erat ligula pharetra, feugiat velit a augue viverra sapien. Risus vestibulum fusce. </p>
  <p> Quam nec sem purus odio lacus ante, sapien sapien mauris fringilla eget, penatibus 
  scelerisque veniam vel vel, sit cras morbi sit. </p>
  </div>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Anton');
  @import url('https://fonts.googleapis.com/css?family=Shadows+Into+Light');
  @import url('https://fonts.googleapis.com/css?family=Encode+Sans+Expanded|Shadows+Into+Light');
  .imagemAbout {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    z-index: -1;
    height: 100%;
  }
  .textoAb  {
    color: rgba(224, 87, 62, 0.85);
    font-size: 80px;
    font-family: Anton;
    right: 110px;
    bottom: 300px;
    position: absolute;
   /* text-shadow: #000000 1px 2px 2px;*/

  }

  .descricao {
    color: white;
    position: absolute;
    font-size: 18px;
    font-family: Encode Sans Expanded|Shadows Into Light;
    box-shadow: #000 2px 2px 1px;
    bottom: 55px;
    left: 160px;
    border: #000 1px solid;
    padding: 10px;
    background-color: rgba(0, 0, 0, 0.3);
  }
  .cabecalho {
    color: white;
    position: absolute;
    font-size: 50px;
    font-family: Shadows Into Light;
    bottom: 120px;
    left: 430px;
    text-shadow: #000000 1px 2px 2px;
  }

</style>

<script>
  function abrirAbout () {
  document.getElementById("t2").innerHTML = "História da empresa";
}
</script>
