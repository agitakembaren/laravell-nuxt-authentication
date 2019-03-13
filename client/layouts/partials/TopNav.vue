<template>
<div>
    <div class="container">
    <b-navbar type="light" variant="light">
    <nuxt-link class="navbar-brand" to="/">Jwt-Authe</nuxt-link>

    <b-navbar-nav>
      <li class="nav-item">
        <nuxt-link class="nav-link" to="/dashboard">Dashboard</nuxt-link> 
      </li>
    </b-navbar-nav>
    <b-navbar-nav class="ml-auto">
      <li class="nav-item">
        <nuxt-link class="nav-link" to="/auth/login">Login</nuxt-link> 
      </li>
      <li class="nav-item">
        <nuxt-link class="nav-link" to="/auth/register">Register</nuxt-link>
      </li>
    </b-navbar-nav>
    </b-navbar>
    </div>

</div>
</template>

