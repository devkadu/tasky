<script lang="ts" setup>
import Input from './components/Input.vue'
</script>

<template>
  <div class="wrapper">
    <div class="content">
      <div>
        <img src="./assets/logo tasky.png" />
        <p>Todas as suas tarefas, em um só lugar.</p>
      </div>
      <form>
        <Input type="text" placeholder="Email" />
        <Input type="password" placeholder="Senha" />
        <button type="submit" class="btn">continuar</button>
        <p>Ou prossiga</p>
        <div class="rede-sociais">
          <img
            src="https://id-frontend.prod-east.frontend.public.atl-paas.net/assets/google-logo.5867462c.svg"
            alt=""
          />

          google
        </div>
        <div class="rede-sociais">
          <img src="https://www.designi.com.br/images/preview/10000171.jpg" />

          facebook
        </div>
        <div class="rede-sociais">
          <img
            src="https://id-frontend.prod-east.frontend.public.atl-paas.net/assets/apple-logo.54e0d711.svg"
            alt=""
          />

          Apple
        </div>
      </form>
    </div>
  </div>
</template>

<style scoped>
.wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.content {
  /* border: 1px solid tomato; */
  max-width: 375px;
  width: 90%;
  height: 600px;
  /* border: 1px solid black; */
  display: flex;
  flex-direction: column;
  /* align-items: center; */
  gap: 40px;
}

.content form {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 20px;
}

.btn {
  width: 400px;
  height: 48px;
  font-size: large;
  font-weight: bold;
}

.rede-sociais {
  width: 400px;
  border: 1px solid lightgray;
  height: 48px;
  border-radius: 4px;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 10px;

  img {
    width: 24px;
    height: 24px;
  }
}
</style>
