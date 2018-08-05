<template>
  <div id="app">
    <Header />
    <router-view/>
  </div>
</template>
<script>
import Header from './components/Header.vue';
export default {
  components: {
    Header
  } 
};
</script>

<style lang="scss">
  @import url('https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700,700i,900');
* {
  margin: 0;
  padding: 0;
  font-family: 'Roboto', sans-serif;
  box-sizing: border-box;
}

.container {
  width: 720px;
  margin: 0;
}

.row {
  display: flex;
  flex-wrap: wrap;
}

@for $i from 1 through 12 {
  .col-#{$i} {
    flex: 0 0 calc(100% / 12 * #{$i});
    max-width: 100%;
  }
}
</style>

