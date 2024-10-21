<template>
  <div
    class="circle-container"
    :style="{ width: `${size}px`, height: `${size}px` }"
  >
    <img :src="src" alt="Circle Image" class="circle-image" />
  </div>
</template>

<script setup lang="ts">
import { defineProps } from 'vue'

// Propsの型定義
interface Props {
  src: string;  // 画像のURLを受け取る
  size?: number;  // オプション: 画像のサイズ (px 単位)
}

// Propsの宣言
const props = defineProps<Props>()

</script>

<style scoped>
.circle-container {
  display: inline-block;
  overflow: hidden;
  border-radius: 50%; /* 画像を円形にする */
  width: 100px; /* デフォルトのサイズ */
  height: 100px; /* デフォルトのサイズ */
}

.circle-image {
  width: 100%;
  height: 100%;
  object-fit: cover; /* 画像をコンテナにフィットさせる */
}
</style>
