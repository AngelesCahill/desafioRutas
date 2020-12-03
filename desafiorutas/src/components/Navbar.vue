<template>
  
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <img src="https://archzine.es/wp-content/uploads/2019/11/8-chica-jersey-en-rayas-blanco-y-negro-gafas-marco-blanco-pelo-recogido-en-mo%C3%B1o-u%C3%B1as-largas-pintas-labios-pintados-dibujos-a-lapiz-faciles-de-copiar.jpg" alt="logo" width="8%" height="8%">
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item active mx-5">
           <router-link to="/">Home</router-link> 
          </li>
          <li class="nav-item mx-5">
            <router-link to="/about">About</router-link>
          </li>
          <li class="nav-item mx-5">
            <router-link to="/contacto">Contacto</router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
          </li>
        </ul>
      </div>
    </nav>
 
</template>

<script>
export default {
  name: 'Navbar',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
