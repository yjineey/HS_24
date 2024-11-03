<template>
  <footer class="footer has-cards">
    <div class="container">
      <hr />
      <div class="col-md-6">
        <div style="width: 990px !important; text-align: right">
          &copy; {{ year }}
          <a
            href="https://github.com/yjineey/HS_24"
            target="_blank"
            rel="noopener"
          >
            yjineey
          </a>
          <span>- All rights reserved</span>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style></style>
