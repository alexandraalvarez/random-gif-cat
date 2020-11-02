<template>
<div id="app" class="my-5">
 
    <randomcat></randomcat>
    
</div>
</template>

<script>
import randomcat from './components/RandomCat.vue'
export default {
    data() {
        return {};
    },
    // computed: {},
    methods: {
        // -- Metodos
    },
    components: {
        'randomcat': randomcat,
    },

}
</script>

<style>
html{
  background-color: lightblue;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: lightblue;
}
</style>
