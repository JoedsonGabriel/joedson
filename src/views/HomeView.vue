<template>
  <div class="home-wrapper">
    <NavBar/>
    <br>
    <b-container>
      <section class="mb-4">
        <Presentation/>
      </section>
      <br>
      <br>
      <hr>
      <br>
      <br>
      <section class="mt-4">
        <Techniques/>
      </section>
      <br>
      <br>
      <hr>
      <br>
      <br>
      <footer>
        <span class="text-default-sm">
          vamos conversar?
        </span>
        <a href="mailto:json.gbriel@gmail.com">json.gbriel@gmail.com</a>
        <br>
        <br>
        <a class="m-1" target="_blank" href="https://www.linkedin.com/in/joedson-gabriel-alves-881124205">
          <img class="social-media-icon" src="img/logos/174857.png" alt="linkedin">
        </a>
        <a class="m-1" target="_blank" href="https://github.com/JoedsonGabriel">
          <img class="social-media-icon" src="img/logos/github.png" alt="github">
        </a>
        <a class="m-1" target="_blank" href="https://www.instagram.com/gabriel.json/">
          <img class="social-media-icon" src="img/logos/Instagram_icon.png" alt="instagram">
        </a>
        <br>
        <br>
      </footer>
    </b-container>
  </div>
</template>
<script>

// Desenvolvo sites e aplicações utilizando HTML, CSS, e JavaScript. Tenho familiaridade em desenvolver layouts que me fornecem. Estou sempre me aprimorando a cada projeto que colocam em minhas mãos.
// <br>
// Sou uma pessoa dedicada que corre atrás para realizar seus sonhos, trabalhador e orientado a resultados, sempre busco alcançar minha melhor versão.
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import NavBar from '@/components/NavBar.vue'
import Presentation from '@/components/Presentation'
import Techniques from "@/components/Techniques"

export default {
  name: 'HomeView',
  components: {
    NavBar,
    Presentation,
    Techniques
  },
  data(){
  }
}
</script>

<style lang="scss">
  .social-media-icon{
    width:60px;
  }
  .img-width{
    height: 300px;
  }
  .home-wrapper{
    .text-default{
      *{
        font-family: 'Starjedi', sans-serif;
        color: #FFE919 !important;
        letter-spacing: 2px;
        font-size: 24px;
      }
      font-family: 'Starjedi', sans-serif;
      color: #FFE919 !important;
      letter-spacing: 3px;
      font-size: 24px;
    }
    .text-default-sm{
      *{
        font-family: 'Starjedi', sans-serif;
        color: #FFE919 !important;
        letter-spacing: 2px;
        font-size: 20px;
      }
      font-family: 'Starjedi', sans-serif;
      color: #FFE919 !important;
      letter-spacing: 3px;
      font-size: 20px;
    }
  }
</style>