<script>
import TitleComponent from './components/AppTitle.vue';
import JumbotronComponent from './components/AppHero.vue';
export default {
  name: 'MyApp',

  components:{
    TitleComponent,
    JumbotronComponent,
  },
};
</script>


<template>

<header>
  <TitleComponent />
</header>

<main>
  <JumbotronComponent />
</main>

</template>
