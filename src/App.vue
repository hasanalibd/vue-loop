<script setup>
// const items = [1,2,3,4,5]
const names = ['Hasan Ali', 'Rakib Uddin', 'Didar Ali', 'Elias Uddin', 'Amrita Das', 'Arif Khan']
</script>

<template>
  <section class="mx-auto container flex items-center text-center flex-col space-y-2">
        <!-- <div class="p-5 border border-gray-600 w-40" v-for="n in 100"> {{ n }}</div> -->
        <!-- <div class="p-5 border border-gray-600 w-40" v-for="item in items"> {{ item }}</div> -->

        <div class="p-5 border border-gray-600 w-40" v-for="name in names"> {{ name }}</div>
    </section>
</template>

<style scoped>

</style>
