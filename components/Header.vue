<template>
  <div class="header">
    <div class="logo">Nuxt Learning</div>
    <div class="btn-wrap">
      <button @click="$router.push('/')">Home</button>
      <button @click="$router.push('/secondPage')">Second Page</button>
    </div>
  </div>
</template>

<style lang="scss" scoped>
* {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  font-family: arial;
  padding: 0;
  margin: 0;
}

body {
  background: #ecf0f1;
  font-family: arial;
  margin: 0;
  color: #888;
}

.header {
  display: flex;
  height: 60px;
  background: #00dafc;
  color: #fff;
  width: 100%;
}

.logo {
  display: flex;
  width: 15%;
  height: 60px;
  line-height: 60px;
  font-size: 20px;
  font-weight: bold;
  margin-left: 30px;
}

.btn-wrap {
  display: flex;
  width: 30%;
  height: 100%;
  margin-left: 60%;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}

.btn-wrap button {
  display: block;
  text-align: center;
  vertical-align: middle;
  text-decoration: none;
  width: 120px;
  height: 40px;
  line-height: 40px;

  font-weight: bold;
  background-image: linear-gradient(to right, #27acd9 0%, #b4e12b 100%);
  border-radius: 100vh;
  color: #fff;
  border: 2px solid #fff;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
  -webkit-box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
  transition: 0.5s;
}

.btn-wrap button:hover {
  color: #fff;
  background-image: linear-gradient(to left, #27acd9 0%, #b4e12b 100%);
}
</style>
