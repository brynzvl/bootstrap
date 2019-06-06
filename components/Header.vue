<template>
  <div class="header clearfix">

    <nav>

      <ul class="nav b-nav-pills float-left">
        <li class="nav-item">
          <nuxt-link  id="logo-link"  class="nav-link" to="/index">Vue.js</nuxt-link>
        </li>
      </ul>

      <ul class="nav b-nav-pills float-right">
        <li class="nav-item">
          <nuxt-link class="nav-link" to="/accordion">Accordion</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link class="nav-link" to="/image">Image</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link class="nav-link" to="/grid">Grid</nuxt-link>
        </li>
      </ul>
    </nav>

  </div>
</template>
