<template>
    <div>
        <div>
            <home-header></home-header>
            <home-swiper></home-swiper>
            <home-icons></home-icons>
            <home-recmmend></home-recmmend>
            <home-weekend></home-weekend>
        </div>
    </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeSwiper from './components/Swiper'
import HomeIcons from './components/Icons'
import HomeRecmmend from './components/Recommend'
import HomeWeekend from './components/Weekend'
export default {
  name: 'Home',
  components: {
    HomeHeader: HomeHeader,
    HomeSwiper: HomeSwiper,
    HomeIcons: HomeIcons,
    HomeRecmmend: HomeRecmmend,
    HomeWeekend: HomeWeekend
  }
}
</script>

<style lang="">
</style>
