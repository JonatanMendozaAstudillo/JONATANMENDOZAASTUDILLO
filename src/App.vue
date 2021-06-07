<template>  
  <!-- <section id='header'>
    <article id='banner'>
      <h1>Mi proyecto</h1>
    </article>
  </section> -->
  <section>
    <nav id='menu'>
      <ul>
        <li><router-link to="/">Inicio</router-link></li>
        <li><router-link to="/about">Saludo</router-link></li>
        <li><a href="tablas.html">Tablas</a></li>
        <li><a href="card.html">Social Media</a></li>
      </ul>
    </nav>
  </section>

  <div class="container-fluid pt-3">
    <router-view></router-view>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;700&display=swap');
@import url('https://necolas.github.io/normalize.css/8.0.1/normalize.css');

/* html, body{ font-family: 'Roboto', sans-serif; } */

#banner {
  background: url(assets/images/symbolic.jpg); 
  height: 300px;
}

#banner h1{
  color: #91BED4;
  text-align: center;
}


#menu{
  padding: 0 10px; 
  background: #91BED4;
  height: 50px;
}
#menu ul{ 
  height: 100%;
  margin: 0;
  padding-left: 0;
  display: flex;
  background: #91BED4;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
}

#menu ul li{ 
  display: inline;
  background: #91BED4;
  margin-right: 30px;
  }

    #menu ul li a{
      text-decoration: none;
      color: #D9E8F5;
    }

    #menu ul li a:hover{
      text-decoration: underline;
      color: #91BED4;
    }
</style>
