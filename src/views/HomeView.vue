<template>
  <div class="home">
    <SideBar />
    <MainView />
  </div>
</template>

<script>
import SideBar from '@/components/SideBar.vue'
import MainView from '@/components/MainView.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld,
    SideBar,
    MainView,
  }
}
</script>
