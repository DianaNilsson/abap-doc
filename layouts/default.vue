<template>
  <div>
    <header>
      <nav>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/introduction">Introduction</NuxtLink></li>
        </ul>
      </nav>
    </header>
    <div><slot /></div>
  </div>
</template>

<style scoped>
  .router-link-exact-active {
    color: darkseagreen;
  }
</style>
