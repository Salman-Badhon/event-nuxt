<template>
  <div>
    <nav>
      <nav-bar />
    </nav>
    <main>
      <hero-section />
      <event-schedule />
    </main>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import HeroSection from '@/components/HeroSection.vue'
import EventSchedule from '@/components/EventSchedule.vue'
export default {
  name: 'HomePage',
  components: { NavBar, HeroSection, EventSchedule },
}
</script>
