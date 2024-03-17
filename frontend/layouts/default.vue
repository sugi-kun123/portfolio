<template>
  <div>
    <HeaderSection />
    <div class="main-contents"></div>
    <FooterSection />
  </div>
</template>

<script>
import HeaderSection from '~/components/Header.vue'
import FooterSection from '~/components/Footer.vue'

export default {
  components: {
    HeaderSection,
    FooterSection
  }
}
</script>

<style>
.footer {
  background-color: aquamarine;
}
</style>
