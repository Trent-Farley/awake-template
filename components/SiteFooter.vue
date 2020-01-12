/* eslint-disable vue/html-closing-bracket-newline */ /* eslint-disable
prettier/prettier */
<template>
  <!-- prettier-ignore-attribute -->
  <footer class="site-footer">
    {{ $siteConfig.siteName }} &copy; {{ new Date().getFullYear() }} - All
    Rights Reserved
    <br />
    <a
      href="https://www.patreon.com/bePatron?u=29177112"
      data-patreon-widget-type="become-patron-button"
      >Become·a·Patron!</a
    >
    <script
      asyncn
      src="https://c6.patreon.com/becomePatronButton.bundle.js"
    ></script>
  </footer>
</template>

<script>
export default {
  name: 'SiteFooter'
}
</script>

<style scoped>
footer {
  background: #eee;
  padding: 20px 10px;
  text-align: center;
  transition: 0.5s ease all;
}
</style>
