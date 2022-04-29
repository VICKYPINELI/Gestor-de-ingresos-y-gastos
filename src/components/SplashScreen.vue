<template>
  <div class="splashscreen">
      <img src="@/assets/logo.png" alt="logo"/>
    <h1><span>Gestor</span> de Gastos</h1>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.splashscreen {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  height: 100vh;
}
h1 {
  color: var(--brand-blue);
}
h1 span {
  color: var(--brand-green);
}
</style>

// Este complemento sirve para que aparezca 
// solo mientras se esta recargando la pagina.