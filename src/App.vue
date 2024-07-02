<script>
export default {
  data() {
    return {
      name: 'World',
      status: false
    }
  }
}
</script>


<template>
  <h1>Hello {{name}}</h1>
  <p v-if="status">User is active</p>
  <p v-else>User is inactive</p>
</template>