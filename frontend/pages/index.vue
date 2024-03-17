<template>
  <div>
    <MainKeyvisual />
    <section class="about">
      <About />
    </section>
    <section class="skills">
      <Skill />
    </section>
    <section class="works">
      <Works />
    </section>
    <section class="contact">
      <Contact />
    </section>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  name: 'IndexPage'
})
</script>
