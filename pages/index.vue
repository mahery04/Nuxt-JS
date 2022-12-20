<template>
  <div class="app">
    <div class="bar"></div>
    <div class="bar-title">
      <div class="logo">
        <img src="~/assets/logo-dilypse.JPG" />
      </div>
    </div>
    <p class="p-title">Formulaire d'information pour </p>
    <div class="form">
      <div class="form-name">
        <b-form-input
      id="inline-form-input-name"
      class="mb-2 mr-sm-2 mb-sm-0"
      placeholder="Jane Doe"
    ></b-form-input>
      </div>
    </div>
  </div>
</template>

<style lang="css">
body {
  margin:0;
  background-color: #F5F5F5;
}

.bar {
  position: absolute;
  background-color: #0047FF;
  width: 100%;
  height: 50vh;
}

.bar-title {
  position: relative;
  background: #FFFFFF;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.12);
  border-radius: 10px;
  width: 35%;
  height: 16%;
  left: 36%;
  top: 88px;
}

.logo {
  padding-left: 10px;
  z-index: 3;
}

.p-title {
  position: fixed;
  top: 12%;
  left: 45%;
  font-family: 'Montserrat';
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 24px;
  color: #5978A9;
}

.form {
  position: absolute;
  background: #FFFFFF;
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.12);
  border-radius: 10px;
  width: 35%;
  height: 50%;
  left: 36%;
  top: 230px;
}
</style>

<script>
export default {
  name: 'IndexPage'
}
</script>



