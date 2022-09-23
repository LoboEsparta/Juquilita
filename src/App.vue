<template>
<div class="Header">
<header-vue></header-vue>
</div>


<div class="Content">

  <card url="https://elmundoenrecetas.s3.amazonaws.com/uploads/recipe/picture/138/como_hacer_flautas_de_pollo_2.webp" nombre="Flautas de Pollo"  descripcion="Flautas de pollo con crema, lechuga y cebolla" costo="45"/>
  <card url="https://cdn-3.expansion.mx/dims4/default/1f61403/2147483647/strip/true/crop/2096x1430+0+0/resize/1200x819!/quality/90/?url=https%3A%2F%2Fcdn-3.expansion.mx%2F95%2F6c%2F722abfb544dcb4a46b9ca967a1ef%2Fistock-499925476.jpg" nombre="Coca Cola"  descripcion="Refresco Coca Cola de 500ml" costo="30 "/>
  <card url="https://cdn7.kiwilimon.com/recetaimagen/35482/42619.jpg" nombre="Tostadas"  descripcion="Tortilla de maiz dorada con frijoles, lechuga, queso y crema" costo="25"/>
  <card url="https://www.eluniverso.com/resizer/bm63roX-33Wcy4t-GYx6fQFZT-Y=/arc-anglerfish-arc2-prod-eluniverso/public/QOPIYEFGAJEQZHLKIGT3GLRO2U.jpg" nombre="Jugo de Naranja"  descripcion="Jugo de Naranja 100% natural" costo="30"/>
  <card url="https://img-global.cpcdn.com/recipes/38df0212b6629a5a/1200x630cq70/photo.jpg" nombre="Huevo Frito"  descripcion="Huevos fritos al gusto" costo="15 "/>
  <card url="https://i.blogs.es/f9190d/smash_burger/1366_2000.jpg" nombre="Hamburguesa"  descripcion="Hamburguesas para los niños del hogar" costo="60 "/>
  
</div>



<FooterVue></FooterVue>

  </template>


<script>
  import Card from "./components/Card.vue";
  import FooterVue from "./components/Footer.vue";
  import HeaderVue from "./components/Header.vue"
  export default {
    components:{
      Card, 
      FooterVue, 
      HeaderVue,
    },
  };

</script>
  
