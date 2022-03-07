<template>
  <div>
    <AppHeader />
    <section>
      <h2>Page Content</h2>
      <p>This section is directly on the index.vue file</p>
      <p>Ashlyn Knox</p>
    </section>
  </div>
</template>

<script>
import { defineComponent } from '@nuxtjs/composition-api'

export default defineComponent({
  name: 'IndexPage'
})
</script>
