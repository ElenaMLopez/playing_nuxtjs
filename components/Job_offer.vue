<template>
    <main class="offers-container">
    <img src="" alt="offer image">
    <h1> {{title}}</h1>
    <p>{{text}}
    </p>
  </main>
</template>

<script>
export default {
  props: ['title', 'text']
}
</script>

