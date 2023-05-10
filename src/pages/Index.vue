<template>
    <div>
        <div class="plano1">
            <div class="logo">
                <img src="../assets/Group 559.svg">
            </div>
            <div class="titulo1">
                <TituloSimples msg="What is Lorem Ipsum"/>
            </div>
            <div class="texto1">
              <p> Lorem Ipsum is simply dummy text of the printing and typesetting industry.
              Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled</p>
            </div>
            <div class="ferramentas">
                <img src="../assets/icoferramenta.svg">
                <img src="../assets/icoferramenta.svg">
                <img src="../assets/icoferramenta.svg">
            </div>
            <div class="help">
              <BotaoHelp msg="Help Me"/>
            </div>
        </div>
        <div class="plano2">
            <div class="container">
              <div class="cont1">
                <div class="titulo2">
                  <TituloSimples msg="What is Lorem Ipsum"/>
                </div>
                <div class="textperto">
                  Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries
                </div>
                <div class="texto1 textocont">
                  <p> <span class="bi_check"></span> Lorem Ipsum is simply dummy text of the printing</p>
                  <p> <span class="bi_check"></span> Lorem Ipsum is simply dummy text of the printing</p>
                  <p> <span class="bi_check"></span> Lorem Ipsum is simply dummy text of the printing</p>
                </div>
              </div>
              <div class="cont2">
              </div>
            </div>
            <div class="help">
              <BotaoHelp msg="Help Me"/>
            </div>
        </div>    
        <div class="plano3">
          <div class="titulo1">
            <TituloSimples msg="Services"/>
          </div>
          <div class="background">
            <img src="../assets/Group 15.png" class="imagem">
          </div>
        </div>
        <div class="plano4">
          <div class="container" style="padding-top: 50px;">
              <div class="quadro1">
                <dvi class="titulo3">
                  Lorem Ipsum
                </dvi>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting </p>
              </div>
              <div class="quadro2">
                <dvi class="titulo3">
                  Lorem Ipsum
                </dvi>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting </p>
              </div>
              <div class="quadro3">
                <div class="titulo3">
                  Lorem Ipsum
                </div>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting </p>
            </div>
            <div class="quadro4">
                <dvi class="titulo3">
                  Lorem Ipsum
                </dvi>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting </p>
            </div>
          </div>  
          <div class="help">
            <BotaoHelp msg="Help Me"/>
          </div>
        </div>
        <div class="plano5">


        </div>
        <div class="plano6">
          
            <h1>Contact Us</h1>
            <div class="container2">
              <img src="../assets/Rectangle 16.png">
              <img src="../assets/Rectangle 16.png">
              <img src="../assets/Rectangle 16.png">
              <img src="../assets/Rectangle 18.png">
            </div>            

        </div>
        <div class="plano7">

        </div>
    </div>
  </template>
  
  <script>
import TituloSimples from '@/components/Titulo.vue';
import BotaoHelp from '@/components/BotaoHelp.vue'

 export default {
    name: 'PageIndex',
    components: {
    TituloSimples,
    BotaoHelp,
  }

  
    
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  .plano1{
    background-image: url('../assets/262012-P4LQCB-641\ 1.png');
    background-repeat: no-repeat;
    background-size: cover ;
    width: 100%;
    height: 840;
    text-align: center;

  }
  .logo{
    padding-top: 130px;
  }
.titulo1{
    padding-top: 181px;
}
.texto1{
    padding-top: 87px;
    color: #fff;
    width: 520px;
    margin: auto;
}
.ferramentas{
    padding-top: 115px;
    display: flex;
    justify-content: space-between;
    align-content: space-between;
    width: 500px;
    margin: auto;

}
.help{
    padding-top:100px ;
    padding-bottom: 100px;
    display: block;
    margin: 0 auto; 
    text-align: center;
}

.plano2{
  width: 100%;
  height: 100vh;
  background: rgb(2,0,36);
  background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(255,255,255,1) 0%, rgba(255,255,255,1) 50%, rgba(80,178,234,1) 50%, rgba(80,178,234,1) 100%);
}


.container{
  padding-top: 100px;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 70%;
  margin: auto;
  border-radius: 20px;
}

.cont1{
  background-color:rgba(80,178,234,1);
  border-radius: 30px 0px 0px 30px;
  text-align: center;


}
.cont2{
  background-image: url('../assets/Rectangle 4.png');
  background-repeat: no-repeat;
  border-radius: 1px solid #fff;
  background-size: cover;
}

.cont1, .cont2{
  float: left;
  width: 50%;
  height: 500px;
}

.titulo2{
  padding: 100px;
}
.textperto{
  color: #19435A;
  font-size: 14px;
  text-align: left;
  padding: 0px 40px 10px 40px;
}

.bi_check{
  background-image: url('../assets/bi_check-circle-fill.png');
  display: inline-block;
  width: 10px;
  height: 10px;
  background-size: cover;
  background-position: center;
  margin-right: 10px;
}

.textocont{
  padding: 40px 40px 10px 40px;
  text-align: left;
  line-height: 2;
}

.plano3{
  background-image: url('../assets/Group 28.png');
  background-repeat: no-repeat;
  background-size: cover ;
  width: 100%;
  height: 360;
  text-align: center;
}

.imagem {
  padding-bottom: 50px;
  padding-top: 50px;
}


.plano4{
  background-color: #fff;
  background-repeat: no-repeat;
  background-size: cover ;
  width: 100%;
  height: 360;
  text-align: center;
}

.titulo3{
  color: #50B2EA;
  font-size: 18px;

}

.quadro1, .quadro2, .quadro3, .quadro4{
}

.plano5{
  width: 100%;
  height: 70vh;
  background: #50B2EA;
}

.plano6{
  width: 100%;
  height: 70vh;
  background: #fff;  
}

h1{
  font-weight: 800;
  font-size: 38px;
  color: #50B2EA;
  text-align: center;
  padding-top: 20px;
  padding-bottom: 20px;
}

.container2{
  display: flex;
  flex-direction: column;
  align-items: center;
}

img {
  margin: 10px 0;
}

.plano7{
  width: 100%;
  height: 10vh;
  background: #19435A;  
}

  </style>