<script setup>
import NavBar from './components/nav/NavBar.vue'
import HeroComponent from './components/HeroComponent.vue'
import MapComponent from './components/map/MapComponent.vue'
import AboutComponent from './components/AboutComponent.vue'
import ContactComponent from './components/ContactComponent.vue'
import FooterComponent from './components/FooterComponent.vue'
import BackgroundComponent from './components/BackgroundComponent.vue'
import BilboardModal from './components/map/BilboardModal.vue'
import BilboardListModal from './components/map/BilboardListModal.vue'
</script>

<template>
  <main>
    <BilboardModal />
    <BilboardListModal />
    <NavBar />
    <HeroComponent />
    <MapComponent />
    <AboutComponent />
    <ContactComponent />
    <FooterComponent />
    <BackgroundComponent />
  </main>
</template>

<style scoped></style>
