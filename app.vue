<template>
  <div class="app-container">
    <Header />
    <TopFilters />
    <div class="main-content">
      <SportsSection />
      <SideFilters />
    </div>
  </div>
</template>

<script setup>
import Header from '@/components/Header.vue'
import TopFilters from '@/components/TopFilters.vue'
import SideFilters from '@/components/SideFilters.vue'
import SportsSection from '@/components/SportsSection.vue'
</script>

<style>
.app-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.main-content {
  display: flex;
  gap: 20px;
}
</style>