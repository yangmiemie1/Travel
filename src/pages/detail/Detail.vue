<template>
    <div>
        <detail-banner></detail-banner>
        <detailh-header></detailh-header>
        <div class="content"></div>
    </div>
</template>

<script>
import DetailBanner from './components/banner.vue'
import DetailhHeader from './components/Header.vue'
export default {
  name: 'detail',
  components: {
    DetailBanner: DetailBanner,
    DetailhHeader: DetailhHeader
  }
}
</script>

<style lang="stylus" scoped>
 .content
   height: 50rem
</style>
