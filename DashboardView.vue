<template>
  <div class="flex-1 py-6">
    <div class="mx-auto max-w-6xl px-4 sm:px-6 lg:px-8">
      <h2
        
      <div class="mt-7 grid grid-cols-1 gap-5 sm:grid-cols-2 lg:grid-cols-3">
      <!-- Card -->
        <div class="overflow-hidden rounded-lg bg-white shadow">
          <div class="p-5">
            <div class="flex items-center">
              <div class="flex-shrink-0">
                <!-- Heroicon name: outline/scale -->
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
          .then((response) => {
            console.log(response.data);
            this.count = response.data;
          })
          .catch((error) => {
            // handle error
            console.log(error);
          });
    },
  },
  created() {
    this.index();
  }
};
</script>