<template>
  <div v-if="user">
    <sidebarVue/>
    <div class="flex flex-col md:pl-64">
      <TopHeader/>
      <main>
        <router-view/>
      </main>
    </di
    TopHeader,
},
  data() {
    return {};
  },
  methods:{
   
  },
  computed: {
    user() {
      return this.$store.state.userData
    }
  }
};
</script>

<style></style>
