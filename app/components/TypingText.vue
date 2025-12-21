<script setup lang="ts">
const props = defineProps<{
  text: string
  speed?: number
}>()

const speed = props.speed ?? 80
const displayed = ref('')
let index = 0

onMounted(() => {
  const interval = setInterval(() => {
    if (index < props.text.length) {
      displayed.value += props.text[index]
      index++
    } else {
      clearInterval(interval)
    }
  }, speed)
})
</script>

<template>
  <span class="typing">{{ displayed }}</span>
</template>

<style scoped>
.typing {
  white-space: nowrap;
}
</style>
