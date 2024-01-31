<template>
  <div>
    <h1>{{ message }}</h1>
    <button @click="changeMessage">Змінити повідомлення</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Привіт, це моє перше Vue.js застосування!'
    };
  },
  methods: {
    changeMessage() {
      this.message = 'Повідомлення було змінено!';
    }
  }
};
</script>

<style scoped>
h1 {
  color: blue;
}
</style>