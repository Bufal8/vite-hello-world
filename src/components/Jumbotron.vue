<!-- Descrizione:
Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell’installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita “La mia prima app con Vite!”
Bonus:
Creare un secondo componente AppHero, che visualizza un jumbotron. -->

<script>
import { ref } from 'vue'


const count = ref(0)
</script>

<template>
    <img src="../assets/jumbotron.jpg" alt="">
    
    <button>Scopri di più</button>
  
</template>

<style scoped>
button {
    border: none;
    border-radius: 10px;
    background-color: #FFC61E;
    color: #BD34FE;
}
</style>
