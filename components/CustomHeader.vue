<template>
<header>
    <h1>{{headline}}</h1>
    <nav>
      <ul>
        <li>
          <NuxtLink to="/">HQ</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/elves">ELVES</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/bigfeet">BIGFEET</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/mermaids">MERMAIDS</NuxtLink>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
  export default {
    name: 'CustomHeader',
    props: ['headline']
  }
</script>

<style lang="scss">
h1 {color: magenta;}
ul {
  list-style: none;
  padding: .5rem;
  background-color: violet;
}
li {
  display: inline-block;
}
</style>