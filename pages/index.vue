<template>
  <div id="home">
    <VideoBg/>


    <articles>
      <banner />
    </articles>

    <about />

    <subscribe />

    <social />
  </div>
</template>

<script>
//Template: https://free-blog.vuetifyjs.com/?ref=vuetifyjs.com
  export default {
    name: 'Home',
    components: {
      VideoBg: () => import('@/components/home/VideoBg'),
      About: () => import('@/components/home/About'),
      Articles: () => import('@/components/home/Articles'),
      Banner: () => import('@/components/home/Banner'),
      Social: () => import('@/components/home/Social'),
      Subscribe: () => import('@/components/home/Subscribe')
    }
  }
</script>

