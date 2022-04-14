<template>
  <h1>{{ msg }}</h1>

  <p>
    HRT Guide 网站目前还在建设中，但你可以阅读这份资料：
  </p>

  <p>
    <a href="https://docs.google.com/presentation/d/1PzE-rmtwBMOrgXcsI_RIDAKTUIe3fx5h-PmEbzRgBBA" target="_blank">
      Shizu's 跨性别女性HRT资料
    </a>
  </p>

</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

</script>

<style scoped>
a {
  color: #42b983;
}
</style>
