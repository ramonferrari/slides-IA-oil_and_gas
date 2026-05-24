<script setup lang="ts">
defineProps<{
  title?: string
}>()
</script>
<template>
  <footer class="rf-bottom-bar">
    <div class="rf-bottom-left">
      {{ title || $slidev.configs.themeConfig?.shortTitle || 'AI SYSTEMS' }}
    </div>
    <div class="rf-bottom-right-group">
      <a
        class="rf-bottom-link"
        href="https://esdigital.petrobras.com.br"
        target="_blank"
      >
        esdigital.petrobras.com.br
      </a>
      <span class="rf-bottom-page">
          {{ $slidev.nav.currentPage }}/{{ $slidev.nav.total }}
      </span>
    </div>
  </footer>
</template>
<style scoped>
/* ════════════════════════════════════════════
   BOTTOM BAR
════════════════════════════════════════════ */
.rf-bottom-bar {
  position: absolute;
  left: 48px;
  right: 48px;
  bottom: 22px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 14px;
  border-top:
    1px solid var(--rf-bottom-border);
  font-size:
    0.72rem;
  letter-spacing:
    0.12em;
  font-family:
    "JetBrains Mono",
    monospace;
}
/* LEFT TEXT */
.rf-bottom-left {
  color:
    var(--rf-bottom-text);
  opacity:
    1;
}
/* RIGHT GROUP */
.rf-bottom-right-group {
  display: flex;
  align-items: center;
  gap: 1.2em;
}
/* RIGHT LINK */
.rf-bottom-link {
  color:
    var(--rf-link);
  font-weight:
    600;
  letter-spacing:
    0.16em;
}
.rf-bottom-link:hover {
  color:
    var(--rf-link-hover);
}
/* PAGE COUNTER */
.rf-bottom-page {
  color:
    var(--rf-bottom-text);
  font-weight:
    500;
}
</style>