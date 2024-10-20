<script setup lang="ts">
// TODO:font-sizeをpropsで管理する
type Props = {
  title: string;
  tag: "1" | "2" | "3" | "4" | "5" | "6";
};
defineProps<Props>();
</script>

<template>
  <div class="title">
    <component :is="`h${tag}`">
      {{ title }}
    </component>
  </div>
</template>

<style>
.title {
  font-size: xx-large
}
</style>
