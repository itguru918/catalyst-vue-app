<template lang="pug">
.page.browse
  PrimaryHero.is-green
    h1.title.inherit-color
      BrowseSvg.hero-title-icon
      span Browse all projects
  
  section.section.page-expand
    .container
      h2.title.is-3.is-marginless Nulla vitae elit libero, a pharetra augue.
      .content
        p Sed posuere consectetur est at lobortis. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
        p Nullam id dolor id nibh ultricies vehicula ut id elit. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Etiam porta sem malesuada magna mollis euismod. Donec sed odio dui. Integer posuere erat a ante venenatis dapibus posuere velit aliquet.
        p Sed posuere consectetur est at lobortis. Cras justo odio, dapibus ac facilisis in, egestas eget quam. Vivamus sagittis lacus vel augue laoreet rutrum faucibus dolor auctor. Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
</template>

<script>
import PrimaryHero from '@/components/PrimaryHero.vue'
import PageFooter from '@/components/PageFooter.vue'

import BrowseSvg from '@/assets/browse.svg'

export default {
  components: { PrimaryHero, PageFooter, BrowseSvg }
}
</script>

<style lang="sass" scoped></style>