<script setup lang="ts">
</script>

<template>
  <div>
    <NuxtPage />
  </div>
</template>

<style lang="scss">
@use '@/assets/index.scss' as *;

body {
  font-family: $font-stack;
  background-color: $navy-grey-darker;
  color: $sand;
  font-size: 1.2rem;
}

h1 {
  color: $tan;
  width: 100%;
  padding-bottom: 12px;
  font-family: $font-stack;
  font-size: 2rem;
  font-weight: 600;
  letter-spacing: 2px;
  text-align: left;
}

h2 {
  color: $tan;
  width: 100%;
  padding-bottom: 12px;
  font-family: $font-stack;
  font-size: 1.8rem;
  font-weight: 600;
  letter-spacing: 2px;
  text-align: left;
}

h3 {
  color: $tan;
  width: 100%;
  padding-bottom: 12px;
  font-family: $font-stack;
  font-size: 1.6rem;
  font-weight: 600;
  letter-spacing: 2px;
  text-align: left;
}

h4 {
  color: $tan;
  width: 100%;
  padding-bottom: 12px;
  font-family: $font-stack;
  font-size: 1.4rem;
  font-weight: 600;
  letter-spacing: 2px;
  text-align: left;
}

a {
  color: $tan;
  text-decoration: none;
}

a:hover {
  color: $brown;
  cursor: pointer;
  transition: 0.2s ease-in-out;
}

strong {
  font-weight: 600;
  color: $navy-grey-light;
}

em {
  color: $white;
}
</style>
