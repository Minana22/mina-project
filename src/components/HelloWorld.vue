<template>
  <div class="main">
    <div class="wrap1">
      <div class="div1">
        <p>Task1</p>
      </div>
      <div class="div2">
        <p>Task2</p>
      </div>
    </div>

    <div class="wrap2">
      <div class="div3">
        <p>Task3</p>
      </div>
      <div class="div4">
        <p>Task4</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.main {
  background-color: rgb(253, 253, 158);
  display: flex;
  justify-content: center;
  align-items: center;
}

.wrap1 {
  display: flex;
  justify-content: center;
}
.wrap2 {
  display: flex;
  justify-content: center;
}
.div1 {
  background-image: url(https://images.unsplash.com/photo-1472289065668-ce650ac443d2?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTJ8fHNpbXBsZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60);
  width: 200px;
  height: 200px;
  margin: 10px;
}
.div2 {
  width: 200px;
  background-image: url(https://images.unsplash.com/photo-1513506003901-1e6a229e2d15?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fHNpbXBsZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60);
  height: 200px;
  margin: 10px;
}
.div3 {
  width: 200px;
  background-image: url(https://images.unsplash.com/photo-1592296429945-93008c7e5a59?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjZ8fHNpbXBsZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60);
  height: 200px;
  margin: 10px;
}
.div4 {
  width: 200px;
  background-image: url(https://images.unsplash.com/photo-1504204267155-aaad8e81290d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mjd8fHNpbXBsZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60);
  height: 200px;
  margin: 10px;
}
.btn1 {
  height: 30px;
  padding: 10px;
  margin: 10px;
}
.btn2 {
  height: 30px;
  padding: 10px;
  margin: 10px;
}
</style>
