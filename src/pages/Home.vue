<template>
  <navbar />
  <section class="home">

    <div class="image">
        <img src="images/Lx.png" alt="">
    </div>

    <div class="content">
        <h3>hi, i am {{name}}</h3>
        <span>{{motto}}</span>
        <p>{{content}}</p>
        <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
    </div>

</section>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },
      data() {
        return {
            name: "Kanhapong Kanhakul",
            motto: "Yo!",
            content: "A gift And a curse is feel everything so deeply",
        }
    }

}
</script>

<style>

</style>