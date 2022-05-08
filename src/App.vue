<template>
  <nav>
    <router-link :to="{name: 'home'}">Home</router-link> |
    <router-link :to="{name: 'todos.index'}">Todos</router-link> |
  </nav>
  <router-view/>
</template>
