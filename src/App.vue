<template>
  <div id="app">
  <Navigation/>
    <h1>Eurosong festival</h1>
<Counter/>

    <div class="c-feedback warning">
     Er is een fout gebeurd
     </div>
     <div class="c-feedback error">
      'T is kapot
      </div>

      <div class="c-feedback succes">
        Tis gelukt
      </div>
  </div>
</template>

<script>

//Import of the whole styling for the app
import style from "./scss/style.scss";
import Navigation from "./components/Navigation.vue";
import Counter from './components/Counter.vue';
export default {
  name: 'App',
  components:{
    Navigation,
    Counter
  }
}
</script>

