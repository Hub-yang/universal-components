<script setup lang="ts">
const router = useRouter()

function navigateTo(name: string) {
  router.push(`/${name}`)
}
</script>

<template>
  <div flex="~ justify-center items-center" gap-2>
    <button btn @click="navigateTo('contextMenu')">
      组件一
    </button>
  </div>
</template>
