<template>
  <div id="main-banner">
    <h1>The Burger Lab</h1>
  </div>
</template>

<script>
export default {
  name: "Banner",
};
</script>

<style scoped>
#main-banner {
  background-image: url(../../public/img/banner.jpg);
  background-position: 0 -550px;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}

#main-banner h1 {
  color: #fff;
  text-align: center;
  font-size: 60px;
  background: #222;
  padding: 20px;
  border-radius: 10px;
  margin-left: 50px;
}
</style>
