<template>
  <div>
    <AppHeader />
    <section>
      <h2>Page Content</h2>
      <p>This section is directly on the index.vue file</p>
      <p>Gibril Adem</p>
    </section>
    <Style>
      h2, h1 { text-align: center; Background: blue; color: red; } p {
      text-align: center; font-weight: 600; font-family: roboto; }
    </Style>
  </div>
</template>

<script>
import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  name: 'IndexPage'
})
</script>
