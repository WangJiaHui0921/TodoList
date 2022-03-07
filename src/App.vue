<template>
  <div>
    <section class="todoapp">
      <header class="header">
        <h1>Todos</h1>
        <input type="text" class="new-todo" />
      </header>
      <section class="main">
        <input type="checkbox" id="toggle-all" class="toggle-all" />
        <label for="toggle-all"></label>
        <ul class="todo-list">
          <Item />
        </ul>
      </section>
      <Footer/>
    </section>
  </div>
</template>

<script>
import Item from "./components/Item.vue";
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  data() {},
  components: { Item ,Footer},
};
</script>

<style lang="scss" scoped>
</style>