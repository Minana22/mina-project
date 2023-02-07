<template>
  <div class="main">
    <header class="head">
      <div class="button">
        <button @click="pageOne()" class="btn1">
          <font-awesome-icon icon="fa-solid fa-user-secret" />
        </button>
        <button @click="pageTwo()" class="btn2">Page 2</button>
      </div>
    </header>
    <div class="content">
      <HelloWorld v-if="showData"></HelloWorld>
      <layoutComponent v-if="hideData"></layoutComponent>
    </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import layoutComponent from "./components/layoutComponent.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    layoutComponent,
  },
  data() {
    return {
      showData: true,
      hideData: false,
    };
  },
  methods: {
    pageOne() {
      if (!this.showData == true) {
        this.showData = true;
        this.hideData = false;
      }
    },
    pageTwo() {
      if (!this.hideData == true) {
        this.hideData = true;
        this.showData = false;
      }
    },
  },
};
</script>

<style scoped>
.head {
  height: 50px;
}
.button {
  background-color: rgb(216, 124, 3);
  display: flex;
  justify-content: flex-end;
  align-items: center;
  width: 100%;
  height: 50px;
}
.main {
  height: 90vh;
  width: 100%;
  display: flex;
  flex-direction: column;
}
.content {
  display: flex;
  justify-content: center;
  align-items: center;
}
.btn1 {
  margin-right: 20px;
}
.btn2 {
  margin-right: 20px;
}
</style>
