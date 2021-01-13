<template>
  <div class="oval-container">
    <!-- SVG icons in here -->
    <div class="title-container">
      <h2>Great news!</h2>
      <p>
        We're pleased to tell you that based on the details you've provided us,
        we believe you could be due a refund of roughly
      </p>
      <h1>£{{ refundVal }}!</h1>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      refundVal: 0
    };
  },
  mounted() {
    // Add switch statement here to serve refundVal based on URL string
  }
};
</script>
