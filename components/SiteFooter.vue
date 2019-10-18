<template>
  <footer class="site-footer is-black">
    <bold>
      <span>
        Rodovia João Gualberto Soares, 789, Sala 03 - Ingleses do Rio Vermelho
      </span>
    </bold>
    <br />
    <span>(48) 3197-1525</span> -
    <span>Contato@zeusservicoscontabeis.com.br</span>
    <br />
    <span id="reserved">
      {{ $siteConfig.siteName }} &copy; {{ new Date().getFullYear() }} - Todos
      os Direitos Reservados
    </span>
    <br />
  </footer>
</template>

<script>
export default {
  name: 'SiteFooter'
}
</script>

<style scoped>
footer {
  background: rgb(0, 0, 0);
  padding: 20px 10px;
  text-align: center;
  transition: 0.5s ease all;
  color: goldenrod;
}
#reserved {
  font-size: 14.5px;
  font-weight: 300;
}
</style>
