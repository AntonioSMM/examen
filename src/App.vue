<template>
  <center><h1> Comida rapida </h1></center>
  <hr />
  <card url = "https://static.educalingo.com/img/en/800/fast-food.jpg" nombre = "Hamburguesa" costo = "$50" des = "Deliciosa hamburguesa con carne doble"/>
  <card url = "https://www.saborusa.com/wp-content/uploads/2019/10/Animate-a-disfrutar-una-deliciosa-pizza-de-salchicha-Foto-destacada.png" nombre = "pizza" costo = "$60" des = "Deliciosa pizza solo de peperoni" />
  <card url = "https://www.comedera.com/wp-content/uploads/2017/08/tacos-al-pastor-receta.jpg" nombre="Tacos" costo = "$55" des = "Tacos al pastor solamente por ahora"/>
  <card url = "https://upload.wikimedia.org/wikipedia/commons/e/e3/Memelas_Oaxaquenos.jpg" nombre = "Memelas" costo = "$40" des = "Orden de 3 memelitas de frijoles con salsa al gusto "/>
  <card url = "https://www.vvsupremo.com/wp-content/uploads/2016/02/900X570_Mexican-Style-Hot-Dogs.jpg" nombre = "Hot-dog" costo = "$25" des = "Hot-dog sencillo, nada especial"/>
  <card url = "https://upload.wikimedia.org/wikipedia/commons/thumb/b/bb/Torta_Cubana.jpg/1200px-Torta_Cubana.jpg" nombre = "Torta" costo = "$45" des="Torta cubana, bien preparada, atascada" />

</template>

<script>
  import Card from "./components/Card.vue"

  export default {
    components: {
      Card,
    },
  };
</script>