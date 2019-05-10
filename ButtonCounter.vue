<template>
  <div>
    <button v-on:click="count++">You clicked me {{ count }} times.</button>
  </div>
</template>

<script>
  export default {
    name: 'ButtonCounter',

    data() {
      return {
        count: 0
      }
    }
  }
</script>