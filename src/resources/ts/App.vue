<script lang="ts" setup>
    import { ref } from 'vue';
    const count = ref(0);
    let a: Number;
</script>

<template>
  <div>
      <button @click="count++">
            Count is {{ count }}
        </button>
    </div>
</template>