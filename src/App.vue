<script lang="ts" setup>
import { testApi } from './api' // note this in volar 1.8.8 or 1.2.0

const name = ref('volar')

testApi()
</script>

<template>
  <div class="h-screen w-screen flex items-center justify-center text-6xl">
    test {{ name }} fast fix
  </div>
</template>
