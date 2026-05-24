<script setup lang="ts">
import BottomBar from "../components/BottomBar.vue"

const props = defineProps({
  title: {
    type: String,
  }
})
</script>

<template>
  <div class="slidev-layout default relative h-full overflow-hidden">

    <!-- Ambient background: orbs + grid + vignette -->
    <div class="rf-ambient" aria-hidden="true">
      <div class="rf-ambient-orb rf-ambient-orb-l"></div>
      <div class="rf-ambient-orb rf-ambient-orb-r"></div>
      <div class="rf-ambient-grid"></div>
      <div class="rf-ambient-vignette"></div>
    </div>

    <div class="rf-slide-content">
      <slot />
    </div>

    <BottomBar :title="props.title" />
  </div>
</template>
