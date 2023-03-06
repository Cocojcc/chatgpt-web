<script setup lang='ts'>
import { defineAsyncComponent, ref } from 'vue'

const Setting = defineAsyncComponent(() => import('@/components/common/Setting/index.vue'))

const show = ref(false)
</script>

<template>
  <footer class="flex items-center justify-between min-w-0 p-4 overflow-hidden border-t dark:border-neutral-800">
    <p>
      Powered by
      <a
        class="text-blue-600 dark:text-blue-500"
        href="https://github.com/Chanzhaoyu/chatgpt-web"
        target="_blank"
      >
        chatgpt-web
      </a>
    </p>
  </footer>
</template>
