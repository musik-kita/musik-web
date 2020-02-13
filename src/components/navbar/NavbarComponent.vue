<template>
  <div id="nav">
    <!-- <div class="navbar container justify-content">
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div> -->
    <nav class="navbar navbar-expand-lg">
      <div class="container">
        <a class="navbar-brand" href="#"><router-link to="/">Musik-Kita</router-link></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link" href="#">Band</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Merchandise</a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
              >Tentang Kami</a>
              <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                <router-link to="/backgroundStory">
                  <a class="dropdown-item" href="#">Latar Belakang</a>
                </router-link>
                <router-link to="/visionMission">
                  <a class="dropdown-item" href="#">Visi & Misi</a>
                </router-link>
                <router-link to="/ourTeam">
                  <a class="dropdown-item" href="#">Tim Kami</a>
                </router-link>
              </div>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Kontak Kami</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<style scoped>
  #nav {
    padding: 0px 0px 0px 0px;
    margin-bottom: 10px;
    background-color: #343a40;
  }

  #nav a {
    font-weight: bold;
    color: #f3f7fa;
  }

  .navbar-toggler {
    background-color: #42b983;
  }

  .navbar-toggler:hover {
    /* background-color: #42b983; */
    border: 2px;
    background-color: #08e6ae;
  }

  .navbar-toggler-icon {
    color: #343a40;
  }

  .dropdown-menu {
    background-color: #343a40;
    /* border-radius: 20%; */
  }

  #nav a.router-link-exact-active {
    color: #42b983;
  }

  .dropdown-item {
    background-color: #343a40;
    border-radius: 20%;
  }

  .dropdown-item::after {
    background-color: #343a40;
  }

  .navbar-nav {
    padding: 5px;
  }

  .dropdown:hover>.dropdown-menu {
    display: block;
  }

  .dropdown>.dropdown-toggle:active {
    /*Without this, clicking will make it sticky*/
    pointer-events: none;
  }
</style>
