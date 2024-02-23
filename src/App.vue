<script setup lang="ts">
import zhCN from 'ant-design-vue/es/locale/zh_CN'
</script>

<template>
  <a-config-provider :locale="zhCN">
    <a-style-provider hash-priority="high">
      <router-view></router-view>
    </a-style-provider>
  </a-config-provider>
</template>
