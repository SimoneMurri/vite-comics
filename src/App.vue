<template lang="">
    <div class="body">
        <header>
            <Header></Header>
        </header>

        <main>
            <Main></Main>
        </main>

        <footer>
            <Footer></Footer>
        </footer>
    </div>
</template>
<script>

import Header from './components/header/Header.vue';
import Main from './components/main/Main.vue';
import Footer from './components/footer/Footer.vue';

export default {
  components: {
    Header,
    Main,
    Footer,
  }
}
</script>
<style lang="">
</style>