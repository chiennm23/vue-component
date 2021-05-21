<template>
  <div>
    <p>My Address: {{ address }}</p>
    <hr>
    <button @click="changeAddress()">Show</button>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      address: 'Nam Định'
    }
  },
  methods: {
    changeAddress: function () {
      this.address = 'Hà Noi';
    }
  }
}
</script>

<style lang="scss">

</style>
