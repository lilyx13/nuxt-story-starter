<template>
  <header>
    <h1>{{ title }}</h1>
    <p>{{ description }}</p>
  </header>
</template>
<script>
import { defineComponent } from '@nuxtjs/composition-api'
export default defineComponent({
  props: {
    title: {
      type: String,
      default() {
        return 'Default Header'
      }
    }
  },
  setup() {
    const description =
      'This is a description coming from the script in the Header component.'
    return {
      description
    }
  }
})
</script>
