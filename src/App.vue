<template>
  <div>
   <h1>{{ title }}</h1>
   <p>{{ greeting() }}</p>
  </div>
</template>

<script>

export default {
data() {
return {
title: 'Your first Vue file, wououou!!'
}
},
methods: {
greeting: function() {
return 'Yo!, what up?!?!';
}
},
  name: "App",
  components: {
    
  }
};
</script>

<style>

</style>
