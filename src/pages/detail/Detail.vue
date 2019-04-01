<template>
    <div>
        <detail-banner></detail-banner>
        <detailh-header></detailh-header>
        <detail-list :list="list"></detail-list>
        <div class="content"></div>
    </div>
</template>

<script>
import DetailBanner from './components/banner.vue'
import DetailhHeader from './components/Header.vue'
import DetailList from './components/List.vue'
export default {
  name: 'detail',
  components: {
    DetailBanner: DetailBanner,
    DetailhHeader: DetailhHeader,
    DetailList: DetailList
  },
  data () {
    return {
      list: [
        {
          title: '成人票',
          children: [
            {
              title: '成人三馆联票',
              children: [
                {
                  title: '成人三馆联票连锁店销售'
                }
              ]
            },
            {
              title: '成人五馆联票'
            }
          ]
        },
        {
          title: '学生票'
        },
        {
          title: '儿童票'
        },
        {
          title: '特惠票'
        }
      ]
    }
  }
}
</script>

<style lang="stylus" scoped>
 .content
   height: 50rem
</style>
