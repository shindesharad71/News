<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <router-link to="/" class="navbar-brand" tag="a"><i class="fa fa-2x fa-newspaper-o" aria-hidden="true"></i> News</router-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item">
        <router-link to="/about" active-class="active" class="nav-link" tag="a"><i class="fa fa-user" aria-hidden="true"></i> About</router-link>
      </li>
    </ul>
  </div>
</nav>
</template>

<style scoped>
nav {
  margin-bottom: 40px;
  height: 70px;
}
</style>
