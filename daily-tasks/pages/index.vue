<template>
  <div class="container">
    <div class="title">A simple app to prioritize your daily tasks</div>
    <div class="description">
      Enter a task and decide whether it is urgent and important, important but
      not urgent, urgent but not important, or neither urgent nor important.
    </div>
    <!-- turn this into components -->
    <div class="container__enter-task"></div>
    <div class="container__list-tasks"></div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style>
.container {
  background-color: aliceblue;
  margin: 40px 30px;
  min-height: 100vh;
  display: block;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 100;
  font-size: 50px;
  color: #04182d;
  letter-spacing: 1px;
  padding: 20px 0;
}

.description {
  font-family: "Helvetica Neue", Arial, sans-serif;
  font-weight: 250;
  font-size: 20px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
</style>
