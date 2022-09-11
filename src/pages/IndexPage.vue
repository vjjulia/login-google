<template>
<div class="main">
  <q-card class="flex container-login">
    <div class="container-logo">
      <img class="image-logo" src="~assets/logo.png">
    </div>
    <div>
        <h1>Login</h1>
    </div>
    <div class="container-gmail">
        <h2 class="texto-gmail">Ir para o Gmail</h2>
    </div>
    <div class="container-components">
        <q-input class="component" outlined v-model="text" label="E-mail ou telefone" />
    </div>
    <div>
      <a class="link" href="https://accounts.google.com/"> Esqueceu seu e-mail? </a>
    </div>
    <di>
      <p class="paragrafo">não está no seu computador? Use janelas de navegação<br>
        privada para fazer login.<a class="link2" href="URL"> Saiba mais</a></p>
    </di>
    <div>
      <a class="conta" href="URL"> Criar conta</a>
    </div>
    <div>
      <q-btn class="buttom" color="primary" label="Próximo" />
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
  h1 {
    position: absolute;
    bottom: 350px;
    text-align: center;
    width: 420px;
    margin: 0px;
    font-size: 25px
  }

.image-logo {
  width: 20%;
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
  position: absolute;
  bottom: 320px;
  font-size: 20px;
  margin: 0px;

}

.container-components {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: 100vw;
}

.component {
  position: absolute;
  bottom: 250px;
  width: 380px
}

.link {
  position: absolute;
  bottom: 180px;
  padding: 22px;
  text-decoration: none;
  color: rgb(39, 137, 235);
}

.paragrafo {
  position: absolute;
  bottom: 100px;
  margin: 22px;
  color: rgb(74, 72, 72);
}

.link2 {
  text-decoration: none;
  color: rgb(39, 137, 235);
}

.conta {
  position: absolute;
  bottom: 25px;
  margin: 22px;
  text-decoration: none;
  color: rgb(39, 137, 235);
}

.buttom {
  position: absolute;
  left: 300px;
}
</style>
