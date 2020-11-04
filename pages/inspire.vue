<template>
  <v-carousel>
    <v-carousel-item
      v-for="(item, i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    />
  </v-carousel>
</template>
<script>
export default {
  data () {
    return {
      items: [
        {
          src: 'https://i.imgur.com/H3DJCbA.png'
        },
        {
          src: 'https://i.imgur.com/xJujQsw.png'
        },
        {
          src: 'https://i.imgur.com/Qn3X5D2.png'
        },
        {
          src: 'https://i.imgur.com/KjEu1mx.png'
        }
      ]
    }
  }
}
</script>
<style>
</style>
