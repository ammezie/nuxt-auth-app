<template>
  <section class="section">
    <div class="container">
      <h2 class="title">My Profile</h2>

      <div class="content">
        <p>
          <strong>Username:</strong>
          {{ this.$auth.user.username }}
        </p>
        <p>
          <strong>Email:</strong>
          {{ this.$auth.user.email }}
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  middleware: ['auth'],
};
</script>
