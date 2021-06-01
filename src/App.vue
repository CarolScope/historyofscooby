<template>
  <div id="app" class="overflow-x-hidden" style="background-color: #B666D9">
    <!-- Navigation bar -->
    <Nav />
    <!-- Header -->
    <Header />
    <!-- Origins slides -->
    <Origins />
    <!-- Timeline and fun facts -->
    <Timeline />

    <section id="history">
      <div class="flex justify-center mt-10 mb-20">
        <div class="w-10/12 rounded-lg flex pb-20 mr-4" style="background-color: #C5D831; height: 500px;">
          <div class="mt-12">
          </div>
        </div>
      </div>
    </section>

  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Header from './components/Header.vue'
import Origins from './components/Origins.vue'
import Timeline from './components/Timeline.vue'

export default {
  name: 'App',
  components: {
    Nav,
    Header,
    Origins,
    Timeline
  }
}
</script>
