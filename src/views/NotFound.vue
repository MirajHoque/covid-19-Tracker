<template>
  <img :src="notFound" alt="not found" class="w-500 h-auto mt-25 ml-auto mr-auto">
</template>

<script>
export default {
    name: 'NotFound',
    data() {
        return {
            notFound: require('../assets/Donut-404.png')
        }
    }

}
</script>

<style>

</style>