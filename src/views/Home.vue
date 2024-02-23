<script setup lang="ts">
import HelloWorld from '@/components/HelloWorld.vue'
import { message } from 'ant-design-vue'

const info = () => {
  message.success('Hello World')
}
</script>

<template>
  <section>
    <h1 class="text-red-400">Home</h1>
    <HelloWorld />
    <a-button type="primary" @click="info">确定</a-button>
  </section>
</template>
