<script setup>
  import Coracao from "/coracaoPreenchido.png";
  import ContornoCoracao from "/contornoCoracao.png";
</script>

<template>
    
    <header>
      <h1><span>Dev</span>Lookup</h1>
      <input type="text" placeholder="Encontre o que precisar" >
    </header>
    <main>
      <section>
        <div>
            <h3>17 de ago, 2024</h3>
            <img :src="Coracao" alt="Ícone de coração preenchido">
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
            <img :src="ContornoCoracao" alt="Ícone de coração com contorno">
        </div>
        <h2>Por que os hiperlinks são azuis em sua maioria?</h2>
        <p>Quem navega na internet, certamente já percebeu que ela conta com diversos recursos para tornar a nossa vida mais fácil. Entre essas opções podemos mencionar os hiperlinks - uma palavra ou termo clicável que direciona o leitor.</p>
      </section>
    </main>

</template>

<style scoped lang="scss">
  
  header{
    background: #17171A ;
    text-align: center;
    padding: 1.7rem;

    h1{
      font-family: "Doto", sans-serif;
      font-size: 3rem;
      color: white;
      margin: 1.8rem;
    }

    span{
      color: #10EC10;
    }

    input{
      width: 46vw;
      padding: 1rem 1.5rem;
      border: none;
      border-radius: 13px;
      background-color: #202024;
      color:white;
      font-family: "roboto", sans-serif; 
     
      

      &::placeholder{
        color:white;
        font-family: "roboto", sans-serif; 
      }
    }   
  }

  main {
    font-family: "Roboto", sans-serif;
    color: white;
    background-color: #121214;
    height: 70vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 2rem;

    div {
        display: flex;
        justify-content: space-between;
        color: #17171a;

        h3{
          color:#10ec10d5;
          font-size: 0.9rem;
          font-family: "roboto", sans-serif;
          margin-bottom: 0.7rem; 
        }

        img {
          height: 21px;
        }
      }
    

    section {
      background: #17171a;
      border: #252529 solid;
      border-radius: 20px;
      width: 75vw;
      height: 54vh;
      padding: 2rem;
      margin: 1.3rem;

      h2,p{
        font-size: 1.2rem;
        font-family: "roboto", sans-serif;
        margin-bottom: 0.7rem; 
      }
      
      &:hover {
        border: solid #10ec10d5;
      }

    }
      
  }

</style>
