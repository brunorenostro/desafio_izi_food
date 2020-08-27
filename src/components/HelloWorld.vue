<template>
  <div class="hello">
    <h2>Horário de funcionamento</h2>
    <div id="horarios">
    <div>
<div class="box1">
  Horários
</div>
<div class="box2">
</div>
</div>
    <p id="horario_escolha">Escolha os horários que seu restaurante abrirá no iZiFood.</p>
    </div>

    <div class="card">
  <div class="rating"><img class="star" src="@/assets/rating.png" alt="">
  <p class="ratingtext">Recomendações do iZiFood para sua cidade</p>
  </div>

  <div class="container-recomendations">
    <span>Fique aberto durante os horários e receba mais pedidos!</span>
    <div class="smoke-card">
      <p>80% dos pedidos são feitos nestes horários diariamente</p>
    </div>
  </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'HelloWorld',
  props: {
    msg: String,
  },
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
#horario_escolha{
  font-size: 18px;
  text-align: left;
  margin-top: 20px;
  font-weight: bold;
  font-family: PROMETO W04 LIGHT;
}
h2{
  color: #323232;
  text-align: left;
  margin-bottom: 20px;
  font-size:26px;
  font-weight: bold;
}
#horarios_text{
text-align: left;
margin:0;
padding:0;
display: block;
color:#FF1528;
font-weight: bold;
font-size: 22px;

}

#half_bar{

  color:#FF1528;
  font-weight: bold;

}

#full_bar{
  color:#D8D8D8;

}

#bar{
  display:flex;
}

*{
  margin:0;
  padding:0;
}

.star{
  max-width: 52px;
  max-height: 52px;
}
.hello{
  max-width: 960px;
  margin: auto;
  margin-top:60px;

}

.card{
  box-shadow: 0 0 4px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  width: 1000px;
  max-height: 400px;
  margin:auto;
  margin-top: 20px;
  display:flex;
padding:20px;
}
.rating{

display:flex;
text-align: left;
max-width:180px;
margin-top:16px;

}

.ratingtext{
font-weight: bold;
margin-left: 8px;
font-size: 14px;

}

.container-recomendations{
  display:block;
  padding:20px;
  font-size:10px;
  font-weight: bold;
}

.smoke-card{
  display:flex;
  font-size:8px;
  font-weight:none;
  width: 800px;
  height: 100px;
  background-color: #F2F2F2;
  border-radius:25px;
  padding-left:30px;
  padding-top:30px;
}

span{
  font-size: 18px;;
}
p{font-size:14px}

.box1{
  font-weight: bold;
  color: #FF1528;
  border-bottom: 3px solid #D8D8D8;
  padding-bottom: 6px;
  text-align: left;
}
.box2{
  border: 3px solid #FF1528;
  width: 5%;
  margin-top: -6px;
}

*{
  font-family:PROMETO;
}
</style>
