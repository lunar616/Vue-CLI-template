<template>
  <div class="wrapper">
    <header>
      <!-- <li v-for="link of links" :key="link.title">
        <router-link :tittle="link.title" :to="link.url">{{ link.title }}</router-link>
      </li> -->
    </header>

    <router-view></router-view>
  </div>
</template>

<script>
export default {
  data() {
    return {
      // links: [
      //   {
      //     title: 'Modals',
      //     url: '/',
      //   },
      //   {
      //     title: 'Lk',
      //     url: '/lk',
      //   },
      // ],
    };
  },
};
</script>