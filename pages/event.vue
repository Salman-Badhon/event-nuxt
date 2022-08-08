<template>
  <div>
    <nav>
      <nav-bar />
    </nav>
    <main>
      <event-info />
    </main>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'
import EventInfo from '@/components/EventInfo.vue'
export default {
  name: 'EventPage',
  components: { NavBar, EventInfo },
}
</script>
