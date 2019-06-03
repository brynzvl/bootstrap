<template>
  <div class="grid-container">
    <div class="container">
      <!-- <img id="space" src="./img/space.png" class="img-fluid" alt="Responsive image"> -->

      <div class="image-box">
        <!-- <img src="./img/traffic.jpg" class="img-fluid" alt="Responsive image">
        <img src="./img/bridge.jpg" class="img-fluid" alt="Responsive image">
        <img src="./img/tunnel.jpg" class="img-fluid " alt="Responsive image">
        <img src="./img/coast.jpg" class="img-fluid " alt="Responsive image">
        <img src="./img/sky.jpg" class="img-fluid " alt="Responsive image">
        <img src="./img/rails.jpg" class="img-fluid " alt="Responsive image"> -->

      </div>
    </div>
    <div>

      <!-- <footer class="footer">
        <p>© Vue.js 2019</p>
      </footer> -->

    </div>
  </div>
</template>

<template>
      <section class="hero_home">
         <app-header></app-header>
          <article>
            <h1>About</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Est, aperiam doloremque possimus nemo incidunt, consequatur quidem facere in ipsam ratione quod? Provident laborum magnam accusantium sequi optio error sunt, sit.</p>
        </article>

            <!-- <img v-for="image in images" :src="image.url" :alt="image.alt" /> -->

        <!-- <app-footer></app-footer> -->
      </section>
</template>


<script>
    // import Header from './header.vue'
    // import Footer from './footer.vue'

    export default {
        components: {
            // 'app-header': Header,
            // 'app-footer': Footer
        },
      data () {
        return {
            images: [
                { url: '../static/1.jpg', alt: 'I love you nature' },
                { url: '../static/2.jpg', alt: 'Now with dog - Rosé' },
                { url: '../static/3.jpg', alt: 'Jeg er i Danmark' },
                { url: '../static/4.jpg', alt: 'Badabimbadabum' },
                { url: '../static/5.jpg', alt: 'Goodmorning el mundo' },
                { url: '../static/6.jpg', alt: 'My white and rosé with paella' },
                { url: '../static/7.jpg', alt: 'Hopla' },
                { url: '../static/8.jpg', alt: 'Watering by night' },
                { url: '../static/9.jpg', alt: 'Life aint so bad at all...' },
                { url: '../static/10.jpg', alt: 'My whitewine' },
                { url: '../static/11jpg', alt: 'First time for everything...winefair!' },
                { url: '../static/12.jpg', alt: 'Lost around 20% of this years yield!' }
            ]
        }
      }
    }
</script>
