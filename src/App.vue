<script>
import PageHeader from './components/PageHeader.vue'
import MainContent from './components/MainContent.vue'
import PageFooter from './components/PageFooter.vue'

export default {
  name: 'App',
  components: {
    PageHeader,
    MainContent,
    PageFooter
  },
  data() {
    return {
      images: []
    }
  }
}
</script>

<template>
  <PageHeader />
  <MainContent />
  <PageFooter />
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1000px;
  margin: 0 auto;
}

ul,
li,
menu,
a {
  list-style: none;
  text-decoration: none;
  color: white;
}
</style>