<template>
  <div>
    <Navbar/>
    <nuxt/>
  </div>
</template>

<script>
import Navbar from '@/layouts/partials/Navbar';

export default {
  components: {
    Navbar,
  },
};
</script>
