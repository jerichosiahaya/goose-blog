<template>
  <div class="bg-gray-200 mx-36 rounded-b pt-5">
    <menu-bar />
    <div class="text-6xl font-bold p-10 pt-16">
      The Goose Blog
    </div>
    <single-newest-article />
    <div class="grid grid-cols-3 gap-10 px-10 pt-2">
      <div class="" v-for="index in 6" :key="index">
        <card-articles />
      </div>
    </div>
  </div>
</template>

<script>
import CardArticles from '~/components/CardArticles.vue'
import MenuBar from '~/components/MenuBar.vue'
export default {
  components: { CardArticles, MenuBar },
  name: 'IndexPage'
}
</script>
