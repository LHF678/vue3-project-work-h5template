<script setup lang="ts">
import { ref } from 'vue'
const text = ref('朴素按钮')
</script>

<template>
  <main>
    <div>
      <van-button plain type="primary">{{ text }}</van-button>
      <van-button plain type="success">{{ text }}</van-button>
    </div>
  </main>
</template>
