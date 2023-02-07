<template>
  <div class="main">
    <div class="wrapper">
      <div class="dv1">
        <p>Task1</p>
      </div>
      <div class="dv2">
        <p>Task2</p>
      </div>
      <div class="dv3">
        <p>Task3</p>
      </div>
      <div class="dv4">
        <p>Task4</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "layoutComponent",
};
</script>
<style scoped>
.main {
  background-color: rgb(253, 253, 158);
  display: flex;
  justify-content: center;
  align-items: center;
}
.wrapper {
  display: flex;
  justify-content: center;
  flex-direction: column;
  align-items: center;
}
.dv1 {
  height: 100px;
  width: 425px;
  margin-bottom: 10px;
  background-image: url(https://images.unsplash.com/photo-1472289065668-ce650ac443d2?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTJ8fHNpbXBsZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60);
}
.dv2 {
  margin-bottom: 10px;
  height: 100px;
  width: 425px;
  background-image: url(https://images.unsplash.com/photo-1513506003901-1e6a229e2d15?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fHNpbXBsZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60);
}
.dv3 {
  margin-bottom: 10px;
  height: 100px;
  width: 425px;
  background-image: url(https://images.unsplash.com/photo-1592296429945-93008c7e5a59?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjZ8fHNpbXBsZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60);
}
.dv4 {
  margin-bottom: 10px;
  height: 100px;
  width: 425px;
  background-image: url(https://images.unsplash.com/photo-1504204267155-aaad8e81290d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mjd8fHNpbXBsZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60);
}
</style>
