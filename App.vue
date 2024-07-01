<template>
  <div v-if="user">
    
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
