<template>
  <div class="azul">
    <div class="negro">
      <h1>Mi pagina web</h1>

      <div class="color-box rosado">
        <h2>Contenido</h2>
        
        <p>Esta es una pagina web de ejemplo</p>
        <p>Dichas etiquetas bla bla bla.</p>
        
        <ul>
          <li>Titulos y subtitulos</li>
          <li>Titulos y subtitulos</li>
          <li>Titulos y subtitulos</li>
          <li>Titulos y subtitulos</li>
          <li>Titulos y subtitulos</li>
        </ul>
      </div>

      <div class="mintic-image">
        <img src="../src/assets/mintic.jpg" alt="Mintic Image">
      </div>

      <div class="color-box azul-claro">
        <h3>Conclusión</h3>

        <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
      </div>
    </div>
  </div>
</template>

<script>
// Javascript
</script>

<style>
  * {
    margin: 0;  
  }

  h1 {
    text-align: center;
    color: white;
    margin-bottom: 20px;
    font-family: cursive;
  }

  h2 {
    font-size: 1.4em;
    margin-bottom: 15px;
  }

  h3 {
    margin-bottom: 20px;
  }

  p {
    margin-bottom: 15px;
  }

  li {
    margin-bottom: 3px;
  }

  img {
    height: auto;
    max-width: 100%;
  }

  .azul {
    background-color: #7A98CF;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .negro {
    border: 2px solid black;
    width: 70%;
    padding: 30px 5%;
  }

  .color-box {
    border-radius: 8px;
    padding: 30px 40px;
  }

  .rosado {
    background-color: #E34481;
  }

  .azul-claro {
    background-color: #5B83D4;
    color: #fff;
    text-align: center;
  }

  .mintic-image {
    width: 85%;
    margin: 15px auto;
  }

  .mintic-image img {
    border: 2px solid #fff;
    border-radius: 40px;
  }
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
