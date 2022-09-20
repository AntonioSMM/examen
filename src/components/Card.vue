<template>
      <Grid>
          <img v-bind:src="url" v-bind:alt="nombre">
          <h2>{{nombre}}</h2>
          <h3>{{costo}}</h3>
          <h4>{{des}}</h4>
      </Grid>

</template>

<script>
      import Grid from './Grid.vue';
          export default {
          props: {
              url: {
                  String,
              },
              nombre: {
                  String,
              },
              costo: {
                String,
              },
              des: {
                String,
              }
          },
          components: { Grid }
      };
      </script>

<style scoped>

      
      img {
            width: 320px;
	      height: auto;
	      min-height: 450px;
	      background: rgb(60, 62, 68);
	      border-radius: 20px;
	      overflow: hidden;
	      padding: 10px 15px;
	      margin-bottom: 24px;
	      margin-right: 10px;
	      transition: all 0.2s linear;
	      cursor: pointer;
	      color: white;
                   
      }
  
  </style>