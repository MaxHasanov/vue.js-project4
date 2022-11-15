<template>
  <div id="app">
    <!-- <HomeView v-on:add="add" :categories="categories" :list="paymentsList"></HomeView> -->
    <HomeView></HomeView>
  </div>
</template>

<script>
import HomeView from './views/HomeView.vue';


export default {
  name: "App",
  components: {
    HomeView,
  },
  // data() {
  //   return {
  //     categories: [
  //       "health",
  //       "transport",
  //       "food",
  //       "Study",
  //     ],
  //     paymentsList: [
  //       { id: 1, category: "food", data: "08.11.2022", count: 235 },
  //       { id: 2, category: "food", data: "10.11.2022", count: 340 },
  //       { id: 3, category: "food", data: "12.11.2022", count: 410 },
  //     ],
  //   };
  // },
  // methods: {
  //   add(formData) {
  //     formData.data = new Date().toLocaleDateString('en-us', { weekday: "long", year: "numeric", month: "short", day: "numeric" })
  //     this.paymentsList.push(Object.assign({}, formData))
  //   }
  // }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
