<script setup>
import HeroImage from '@/components/HeroImage.vue';
</script>
<template>
  <div class="home constrained">
    <HeroImage
      title="Willkommen"
      description="Lorem ipsum dolor sit amet,
      consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et
      dolore magna aliquyam erat,sed diam voluptua. At vero eos et accusam et justo duo
      dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem
      ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed
      diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed
      diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita
      kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet."
      :image="require('@/assets/hero_home.png')"
      :parallax=true
    />
  </div>
</template>
