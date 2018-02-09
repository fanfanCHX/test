<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <input v-model="msg">
    <input v-model="msg">
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Hello app de test GIT 2'
    }
  }
}
</script>
