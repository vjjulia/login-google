<template>
<div class="main">
  <q-card class="flex container-login">
    <div class="container-logo">
      <img class="image-logo" src="~assets/logo.png">
    </div>
    <div class="container-texto-login">
        <h1 class="texto-login">Login</h1>
    </div>
    <div class="container-gmail">
        <h5 class="texto-gmail">Ir para o Gmail</h5>
    </div>
    <div class="container-components">
        <q-input class="component" outlined v-model="text" label="E-mail ou telefone" />
    </div>
  </q-card>
</div>
</template>
<style>
.main {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  background: #fff;
  height: 100vh;
  width: 100vw;
}

.container-login {
  height: 500px;
  width: 430px;
  border-radius: 8px;
  padding: 8px;
}

.container-logo {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: 100px;
  width: 100vw;
}

.image-logo {
  width: 20%;
}

.container-texto-login {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: 100px;
  width: 100vw;
  margin-top: 100px;
}

.texto-login {
  margin-bottom: 375px;
  font-size: 20px;
  font-weight: normal;
}

.container-gmail {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: 60px;
  width: 100vw;
}

.texto-gmail {
  margin-bottom: 530px;
  font-size: 20px;
}

.container-components {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: 100vw;
}

.component {
  margin-top: -500px;
  width: 380px;
}
</style>
