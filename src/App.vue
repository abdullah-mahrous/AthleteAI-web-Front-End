<template>
  <Navbar/>
  <Footer/>
  <router-view/>
</template>

<script>
import Footer from './components/footer.vue';
import Navbar from './components/navbar.vue';

export default{
  components: { Footer, Navbar },
}
</script>

<style>

</style>
