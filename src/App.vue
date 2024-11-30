<script setup>
  import Coracao from "/coracaoPreenchido.png";
  import ContornoCoracao from "/contornoCoracao.png";
</script>

<template>
    
    <header>
      <h1>DevLookup</h1>
      <input type="text" placeholder="Encontre o que precisar" >
    </header>
    <main>
      <section>
        <div>
            <h3>17 de ago, 2024</h3>
            <img :src="Coracao" alt="">
        </div>
        <h2>O que é linguagem de programação? Conheça as principais</h2>
        <p>Uma das mais populares vertentes da tecnologia da informação, a área de programação segue tendo muita demanda de trabalho justamente pela velocidade com que dispositivos tecnológicos vêm avançando.</p>
      </section>

      <section>
        <div>
            <h3>12 de jul, 2024</h3>
            <img :src="ContornoCoracao" alt="">
        </div>
        <h2>GitHub agora permite fazer login sem precisar de senha</h2>
        <p>O GitHub anunciou nesta quarta-feira (12) o acesso a partir das passkeys, método de autenticação sem senhas. A novidade está disponível em uma versão beta pública e pode substituir a autenticação em dois fatores.</p>
      </section>

      <section>
        <div>
            <h3>21 de jun, 2024</h3>
            <img :src="ContornoCoracao" alt="">
        </div>
        <h2>Por que os hiperlinks são azuis em sua maioria?</h2>
        <p>Quem navega na internet, certamente já percebeu que ela conta com diversos recursos para tornar a nossa vida mais fácil. Entre essas opções podemos mencionar os hiperlinks - uma palavra ou termo clicável que direciona o leitor.</p>
      </section>
    </main>

</template>

<style scoped lang="scss">

</style>
